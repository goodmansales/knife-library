# Knife Library

The knifelibrary.com site — a research archive for Case XX pocketknife collectors.

## What's here

This is a plain static site (HTML, CSS, and vanilla JavaScript — no framework, no build step), so it deploys on Vercel with zero configuration, same as before.

- `index.html` — home page
- `patterns.html` + `patterns/*.html` — Patterns & Models, with search/filter and a page per pattern
- `materials.html` + `materials/*.html` — Handle Materials, with search/filter and a page per material
- `tang-stamps.html` — the tang stamp dating timeline
- `identify.html` — the "Identify a Knife" tool (filter by blade count and handle shape)
- `data/patterns.json`, `data/materials.json` — the content that drives the search/filter pages and detail pages
- `js/` — the search, filter, and identify-tool logic
- `styles.css` — shared styling

## Updating this site

Any time you want something changed — new patterns, corrected data, a different look, real photos swapped in for the placeholders — describe it to Claude and it'll make the change and give you a new version to upload. You don't need to edit anything by hand.
