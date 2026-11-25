# Third-party notices

All product, project and company names mentioned (for example Microsoft, Playwright, Firecrawl, Anthropic, Claude, OpenAI, Codex, Superpowers, Caveman, Impeccable, UI UX Pro Max) are trademarks or names of their respective owners. They are used only to describe compatibility and content. No affiliation or endorsement is implied.

## Grilling and Grill Me

Author: Matt Pocock. License: MIT.

Upstream repository: https://github.com/mattpocock/skills

Upstream paths:
- skills/productivity/grilling/SKILL.md
- skills/productivity/grill-me/SKILL.md

License source: https://github.com/mattpocock/skills/blob/main/LICENSE

Copied on 2026-11-25 from the existing local skill installation, including its UI metadata. All four supplied files are byte-identical to that local installation. Upstream SKILL.md content was inspected on the same date and matches, except that grilling differs from upstream in blank lines only (whitespace, no content change). The exact installed upstream revision is unknown; the hashes below identify the bundled files. No upstream version number is asserted.

SHA-256:

- `caaf8b8de1684f96e26b28f3c29189db5c89cce4b73e1c93d86164f66ef88637` — `skills/grill-me/SKILL.md`
- `c061e39c3e0f9d865fb1b97556d485704af2a8a58f4b8221a8917a5c2074a32b` — `skills/grill-me/agents/openai.yaml`
- `a146842ed93ca43d833550fa9adf02e58cb63c83fea9d4b4522995b82242d4e2` — `skills/grilling/SKILL.md`
- `1411d7df7d99b7e621a1ff8283c8133cc2464be63d064e52d8ce169c6800ee9b` — `skills/grilling/agents/openai.yaml`

### MIT License

Copyright (c) 2026 Matt Pocock

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Playwright CLI skill

Author: Copyright (c) Microsoft Corporation. License: Apache-2.0 (full text in [licenses/Apache-2.0.txt](licenses/Apache-2.0.txt)).

Upstream repository: https://github.com/microsoft/playwright-cli, path `skills/playwright-cli`, commit `dc5f4d5616ab5a28ded12fd7101a4d49bd59a820` (2026-11-24). Copied unchanged on 2026-11-25. The upstream skill directory and repository root contain no NOTICE file. The skill needs the CLI: `npm install -g @playwright/cli@latest`.

SHA-256:

- `1c4c34000f6102ee71fe91bf25351a221f7da37f48f2d556e1756f66e17d356f` — `skills/playwright-cli/SKILL.md`
- `bf19aa4671e0a50a0fefa9c790f39124e803060eefe395042b723c29fcb7faa2` — `skills/playwright-cli/references/element-attributes.md`
- `c5b0719fef2cfdff50bd744051b2f9afc119775db4b48e9b2882c1cf3886797c` — `skills/playwright-cli/references/playwright-tests.md`
- `24b118e74598be72e73e24fe223d295b9099c85b1860a7c8f6e5690c9038fa2a` — `skills/playwright-cli/references/pr-attachments.md`
- `54e801c9663fc2b6d68ceb058cb1c360724c2499f42acc7852a68e83e5b5f37c` — `skills/playwright-cli/references/request-mocking.md`
- `eac97e0b77e723f8b1d7b64f276f92efa72f74453f45a805352d27ea1853a495` — `skills/playwright-cli/references/running-code.md`
- `2f4d953136cbfb998136095c064c38f4223ea049d6e13610e17db078dde8971c` — `skills/playwright-cli/references/session-management.md`
- `71e90f774b5a7d61367f2336940f30be7c5693d43197b63d1154634b99ae5045` — `skills/playwright-cli/references/storage-state.md`
- `b9c5dda349a469b9abf9f10f3787135e6521f433f5743de399a164e14e76f7ce` — `skills/playwright-cli/references/test-generation.md`
- `4e397e16e6bd92d8696cb815c4ee6dc4ce0be1da9e760e261a9c30b44c7857c7` — `skills/playwright-cli/references/tracing.md`
- `1c800b897824cb54394c34265d8ebffdbb530adfc8d612c5d798b667a1799f48` — `skills/playwright-cli/references/video-recording.md`

## Convert documents to Markdown

Author: Sideguide Technologies Inc. (Firecrawl). License: MIT.

Upstream repository: https://github.com/firecrawl/anydoc, path `skills/convert-documents-to-markdown`, commit `6feb6c2aedd69b97fa8af112ffeb187dcf79986e` (2026-11-18). Copied on 2026-11-25.

**Modified:** Rule 5 in `SKILL.md` was changed so that hosted OCR (`--ocr hosted`, upload to Firecrawl) runs only after the user explicitly agrees for that file and is never offered for company, customer or personal data. A modification note was added below the title. Hash below is of the modified file.

SHA-256:

- `1774730df79ad1636185b8cb71802102f39c12bae9986589fcc1a0f61d05f57b` — `skills/convert-documents-to-markdown/SKILL.md`

### MIT License

MIT License

Copyright (c) 2026 Sideguide Technologies Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## Skill Creator

Original plugin by Anthropic: https://github.com/anthropics/claude-plugins-official, path `plugins/skill-creator`.
License: Apache-2.0. Referenced by the marketplace and pinned to a fixed commit; source is fetched from upstream on installation.

## Impeccable

Original plugin by Paul Bakaus: https://github.com/pbakaus/impeccable, path `plugin`.
License: Apache-2.0. Referenced by the marketplace and pinned to a fixed commit; source is fetched from upstream on installation.

## UI UX Pro Max (includes `slides`)

Original plugin by nextlevelbuilder: https://github.com/nextlevelbuilder/ui-ux-pro-max-skill.
License: MIT. Referenced by the marketplace and pinned to a fixed commit; source is fetched from upstream on installation. The `slides` skill is part of this plugin.

## Superpowers

Original plugin by Jesse Vincent: https://github.com/obra/superpowers
License: MIT. Referenced by the marketplace and pinned to a fixed commit; source is fetched from upstream on installation.

## Caveman

Original plugin by Julius Brussee: https://github.com/JuliusBrussee/caveman
License: Apache-2.0. Referenced by the marketplace and pinned to a fixed commit; source is fetched from upstream on installation. Claude uses the repository root; Codex uses plugins/caveman, matching the installed original package layout.
