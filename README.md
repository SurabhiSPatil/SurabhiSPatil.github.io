# Portfolio

Single-page portfolio site. Self-contained `index.html`, no build step, no dependencies beyond two Google Fonts (Source Serif 4, Inter) loaded via CDN.

## Running locally

Open `index.html` directly in any browser. No server required.

## Deploying

**GitHub Pages:** keep the file named `index.html` at the repo root, enable Pages in repo settings (Settings → Pages → Deploy from branch), and it will serve automatically at `https://<username>.github.io/<repo>/`.

**Anywhere else:** the file can be renamed freely and opened locally or hosted on any static file host, nothing inside depends on the filename.

## Editing content

All content lives directly in the HTML. Section anchors used by the nav bar:
- `id="leadership"` — Strategy and Leadership
- `id="systems"` — Systems and AI Tooling
- `id="experience"` — Experience and Education
- `id="recommendations"` — Recommendations

Open the file in any text editor and search for the section you want to change. Each content block (a leadership highlight, a project entry, a timeline row) follows a repeating HTML pattern; copy an existing block's structure when adding a new entry to stay visually consistent.

## Notes for future edits

- Scroll animations and the sticky highlight panel are driven by vanilla JavaScript at the bottom of the file (IntersectionObserver-based). No external JS libraries.
- Respects `prefers-reduced-motion`: animations are disabled automatically for users with that OS setting on.
- Color and spacing values are defined as CSS custom properties (`:root` block at the top of the `<style>` tag); edit those to retheme the whole page at once.

## Last updated

2026.
