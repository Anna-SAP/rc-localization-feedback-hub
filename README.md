# Localization Feedback Hub — Public Demo

A self-contained demo of a localization-feedback workflow: collect issues (5 input
modes), auto-check proposed German fixes against a glossary + style guide, triage on
a board, and export. One HTML file, no install, works offline.

**This is the public build** — it uses representative data only. Internal product
screenshots, audio, reporter names, and internal system URLs have been removed.

## Publish on GitHub Pages
1. Put these files at the repo root: `index.html` and `.nojekyll`.
2. Settings → Pages → Deploy from a branch → `main` / root.
3. The bare URL serves the app, e.g. `https://anna-sap.github.io/rc-localization-feedback-hub/`.

`.nojekyll` makes Pages serve the file as-is (no Jekyll), so `index.html` is the
homepage instead of a rendered README.
