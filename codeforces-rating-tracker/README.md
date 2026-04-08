# ⟨/⟩ Codeforces Rating Tracker

Simple tool to track and visualize Codeforces rating changes over time.

![Screenshot](https://img.shields.io/badge/status-live-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue)

## Features

- **Interactive Rating Chart** — Line chart with tooltips showing contest name, rank, and rating delta
- **Stats Dashboard** — Current rating, peak, lowest, total contests, average delta, 30-day change
- **Contest History Table** — Sortable table with color-coded deltas
- **Local Caching** — Rating data cached in localStorage with timestamps (auto-refreshes after 30 min)
- **URL Query Params** — Use `?handle=USERNAME` to embed in Notion or any iframe
- **Fully Responsive** — Works on desktop, tablet, and mobile
- **Zero Dependencies** — Pure HTML + Tailwind CSS (CDN) + Chart.js (CDN) + vanilla JS

## Usage

### Option 1: Open locally
Just open `index.html` in a browser.

### Option 2: GitHub Pages
1. Fork this repo
2. Go to **Settings → Pages → Source: main branch**
3. Visit `https://yourusername.github.io/codeforces-rating-tracker/`

### Option 3: Embed in Notion
Use the URL with a query param:
```
https://yourusername.github.io/codeforces-rating-tracker/?handle=tourist
```
Add it as an **Embed** block in Notion for daily monitoring.

## Tech Stack

| Layer | Tech |
|-------|------|
| Markup | HTML5 |
| Styling | Tailwind CSS (CDN) |
| Charts | Chart.js 4.x (CDN) |
| Logic | Vanilla JavaScript |
| Data | Codeforces Public API |
| Storage | localStorage |

## Project Structure

```
codeforces-rating-tracker/
├── index.html      # Complete app (single file)
├── README.md
├── LICENSE
└── .gitignore
```

## Future Scope

- Contest reminders via browser notifications
- Auto-tagging for contest types (Div 1/2/3/4, Educational, etc.)
- Rating prediction based on historical trends
- Multi-handle comparison view

## License

[MIT](LICENSE)
