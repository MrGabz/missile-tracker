# 2026 Iran War -- Missile Launches Tracker

Interactive 3D visualization of missile, drone, cruise missile, and rocket launches during the 2026 Iran War (Feb 28 -- present).

## Features

- MapLibre GL + deck.gl 3D arc visualization of all launch trajectories
- 197 verified launch events from multiple sources (Wikipedia, ACLED, Al Jazeera, Amnesty International, JINSA, JPost, CSIS)
- Filterable by projectile type (ballistic, cruise, drone, rocket, naval), origin country, and date range
- Real-time statistics: total launched, intercepted, hit rate, casualties, cost estimates
- Timeline slider for day-by-day playback
- Responsive design

## Data Sources

Launch data compiled from:
- Wikipedia (2026 Iranian strikes on Israel, 2026 Iran War)
- ACLED (Armed Conflict Location & Event Data)
- Al Jazeera live tracker
- Amnesty International
- JINSA, JPost, FDD, CSIS, Haaretz, Times of Israel

## Deployment

This is a fully static site. Serve `index.html` from any static host (GitHub Pages, Netlify, etc.).

```
missile-tracker-site/
  index.html          # Main visualization (single-page app)
  data/launches.json  # 197 launch events with coordinates and interceptor data
  README.md
```

## GitHub Pages

Deployed at: https://MrGabz.github.io/missile-tracker/
