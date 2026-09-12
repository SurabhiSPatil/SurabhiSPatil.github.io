# Surabhi Patil — Portfolio

A single-page portfolio built around one idea: quality strategy and leadership sit above tooling, which sits above raw skills — the page's layout argues that hierarchy instead of just stating it.

**Live structure**

| Layer | Contents |
|---|---|
| `L01` Strategy & Leadership | Process design, cross-team/cross-department leadership, informal team leadership on AI tooling adoption |
| `L02` Systems & AI Tooling | Shipped AI-enabled QE projects (test generation, coverage analysis, sprint health reporting) |
| `L03` Foundation | Core technical skillset — languages, testing, frameworks, infra, data |
| `L04` Experience | Role history and education |

## Tech

Single self-contained `index.html` — no build step, no dependencies beyond two Google Fonts (Source Serif 4, IBM Plex Mono, Inter) loaded via CDN. Open the file directly in any browser, or serve it as a static site.

## Deploying

**GitHub Pages:** keep the file named `index.html` at the repo root, enable Pages in repo settings (Settings → Pages → Deploy from branch), and it will serve automatically at `https://<username>.github.io/<repo>/`.

**Anywhere else:** the file can be renamed freely and opened locally or hosted on any static file host — nothing inside depends on the filename.

## Updating content

All content lives directly in the HTML — search for the section you want to edit:
- `id="leadership"` — Layer 01 entries
- `id="systems"` — Layer 02 project entries
- `id="foundation"` — Layer 03 skill tags
- `id="experience"` — Layer 04 role/education rows

Each entry follows the same pattern: a title, a right-aligned metric, and a one- to two-sentence description. Keep new entries in that shape to stay visually consistent.

## Last updated

2026 — reflects 8 years of experience.
