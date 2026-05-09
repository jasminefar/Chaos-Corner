# Chaos Corner

A fast, cartoon boxing browser game built as a single-page HTML canvas app.

## Play

Open `index.html` in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Controls

- `WASD` or arrow keys: move around the ring
- `Space`: hold to block
- `P`: pause
- Mobile: tap the on-screen movement, block, pause, and quick shuffle buttons

## Goal

Survive the 60-second bout. Dodge incoming gloves, block punches to score counters, and collect teal towels to recover health.

## Deploy

This repository includes a GitHub Pages workflow at `.github/workflows/pages.yml`. After pushing to GitHub, enable Pages with **GitHub Actions** as the source if it is not enabled automatically.
