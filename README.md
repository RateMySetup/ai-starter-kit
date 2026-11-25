# AI Starter Kit

Ein geprüftes Grund-Setup für alle, die mit **Claude Code** oder **Codex** anfangen. Mit wenigen Befehlen installierst du Skills und Plugins, die im Alltag sofort helfen: Ziele klären, sauber planen, Dokumente lesen, Webseiten bedienen, Präsentationen und Oberflächen gestalten.

## Was ist drin?

### Im Starter-Plugin `ai-starter-kit`

| Skill | Wofür | Aufruf (Beispiel) |
|---|---|---|
| `grilling`, `grill-me` | Stellt dir gezielte Fragen, bis Ziel und Plan klar sind | `/ai-starter-kit:grilling` |
| `playwright-cli` | Bedient einen Browser: Seiten öffnen, klicken, Formulare, Screenshots | „Öffne example.com und lies die Preise aus“ |
| `convert-documents-to-markdown` | Macht Word, Excel, PowerPoint und PDF lesbar und spart dabei Token | „Fasse mir angebot.pdf zusammen“ |

### Weitere Plugins aus dem Katalog (Originale)

| Plugin | Wofür |
|---|---|
| [Superpowers](https://github.com/obra/superpowers) | Strukturiert arbeiten: Ideen klären, planen, testen, Fehler suchen |
| [Caveman](https://github.com/JuliusBrussee/caveman) | Kurze, knappe Antworten. Spart Token und Lesezeit |
| [Skill Creator](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/skill-creator) | Eigene Skills bauen, verbessern und testen |
| [Impeccable](https://github.com/pbakaus/impeccable) | Oberflächen gestalten, prüfen und verfeinern |
| [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | Design-Werte (Farben, Schriften, Stile) und HTML-Präsentationen mit `slides` |

Die Originale werden direkt aus ihren Repositories installiert, jeweils auf einem geprüften, festen Stand. Neue Stände übernimmt dieses Kit erst nach einer Prüfung.

## Voraussetzungen

Einmal auf deinem Rechner einrichten:

1. **Claude Code** (oder Codex) mit Anmeldung
2. **Git**
3. **Node.js 20 oder neuer**: https://nodejs.org
4. **Python 3** (für UI UX Pro Max; auf macOS meist vorhanden)
5. **Playwright CLI** für den Browser-Skill:

   ```bash
   npm install -g @playwright/cli@latest
   ```


## Installation in Claude Code

In Claude Code nacheinander eingeben:

```text
/plugin marketplace add RateMySetup/ai-starter-kit
/plugin install ai-starter-kit@ai-starter-kit
/plugin install superpowers@ai-starter-kit
/plugin install caveman@ai-starter-kit
/plugin install skill-creator@ai-starter-kit
/plugin install impeccable@ai-starter-kit
/plugin install ui-ux-pro-max@ai-starter-kit
```

Danach Claude Code neu starten. Updates holst du mit `/plugin marketplace update ai-starter-kit`.

### Erster Test

```text
/ai-starter-kit:grilling
Ich möchte meinen ersten Arbeitsablauf mit KI vereinfachen. Hilf mir, das Ziel zu klären.
```

## Codex

Der Codex-Katalog liegt unter `.agents/plugins/marketplace.json` und enthält dieselben Bausteine.

**Stand: Entwurf.** Der Installationstest in Codex steht noch aus, und die Originale sind dort noch nicht auf einen festen Stand fixiert. Den Alias `grill-me` in Codex nicht verwenden, sondern `grilling` direkt auswählen.

## Gut zu wissen

- **Dokumente und Datenschutz:** `convert-documents-to-markdown` arbeitet lokal. Nur gescannte PDFs bräuchten einen externen Dienst (Firecrawl). Das passiert nie ohne deine ausdrückliche Zustimmung. Firecrawl sitzt in den USA. Firmen- und Kundendokumente sowie Dateien mit Personendaten dort nie hochladen.
- **Browser-Sitzungen:** Gespeicherte Sessions, Storage-States, Traces und Videos von `playwright-cli` können Zugangsdaten und Personendaten enthalten. Nicht committen und nicht teilen.
- **Astryx (optional, nur React):** Wer React-Apps baut, kann zusätzlich das Design-System [Astryx](https://github.com/meta/astryx) nutzen: `npm i -g @astryxdesign/cli`, dann im Projekt `astryx init`.
- Der Alias `/ai-starter-kit:grill-me` ruft intern `grilling` auf. Klappt das nicht, `/ai-starter-kit:grilling` direkt nutzen.

## Herkunft und Lizenzen

Herkunft, Lizenzen, Änderungen und Prüfsummen aller übernommenen Dateien stehen in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md). Jede Lizenz der Originale gilt für deren Inhalte.

Die eigenen Teile dieses Repositorys (Dokumentation, Manifeste, Kataloge) stehen unter der [MIT-Lizenz](LICENSE). Die übernommenen Skills unter `skills/` behalten ihre eigenen Lizenzen, siehe [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
