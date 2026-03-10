# 🌍 Earth Workforce Evolution

**Interactive globe visualising AI displacement of back-office jobs globally, 2025–2035**

[**→ Live Demo**](https://your-username.github.io/earth-workforce-evolution)

---

## What it shows

A data-driven interactive visualisation of how AI is reshaping the global workforce across 6 tabs:

| Tab | Content |
|-----|---------|
| 🌐 **Map** | Spinning 3D globe with risk spikes per region. Drag to rotate, click to inspect. |
| 👥 **Nations** | Nation-by-nation Crisis Scores — 9 countries with compound risk analysis |
| 📊 **Observatory** | Tableau-style charts: back-office workers by region & sector, 2000–2030 |
| 📉 **GDP** | 10-year GDP shock projections across 4 major regions |
| ⚔️ **Conflict** | 5 geopolitical conflict vectors triggered by AI displacement |
| 🌱 **Opportunity** | 6 emerging job categories with salary ranges and growth projections |

## Features

- **Zero dependencies** — single HTML file, no npm, no build step
- **Pure Canvas 2D globe** — auto-rotates, drag to spin, click spikes to inspect regions
- **Year slider 2025–2035** with animated playback
- **33+ countries** with yearly risk data
- **Hover tooltips** on all top-bar statistics

## Publish to GitHub Pages (3 steps)

1. Create a new GitHub repo (e.g. `earth-workforce-evolution`)
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages → Source → Deploy from branch → main / (root)**

Your site will be live at `https://your-username.github.io/earth-workforce-evolution`

## Local use

Just open `index.html` in any modern browser — no server needed.

```bash
# Or serve locally with Python
python3 -m http.server 8080
# then open http://localhost:8080
```

## Tech stack

- React 18 (via CDN unpkg)
- Babel Standalone (JSX transpilation in-browser)
- Pure HTML5 Canvas 2D (globe rendering)
- Zero external data dependencies — all data inline

## Data notes

All figures are projections based on published research from McKinsey Global Institute, World Economic Forum, Oxford Economics, and World Bank reports on AI and automation. Historical data (2000–2024) draws from ILO employment statistics. Post-2024 figures are modelled scenarios, not predictions.

## License

MIT — free to use, modify, and republish.
