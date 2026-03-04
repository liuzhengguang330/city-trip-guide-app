# City Trip Guide App

Mobile-first one-day trip guide PWA with city switching and persona-based itinerary planning.

## Live Demo
- Stable free URL (CDN): [Open App](https://cdn.jsdelivr.net/gh/REAILab-works/city-trip-guide-app@main/index.html)
- GitHub repo: [city-trip-guide-app](https://github.com/REAILab-works/city-trip-guide-app)

## Why It Gets Attention
- City switch: Berlin / Paris / Tokyo
- Persona planning: standard / speed / relax / foodie
- Interactive map styles: local / OSM / topo
- One-click copy for social post text
- PWA install support

## Privacy Hardening
- No local absolute path, token, private key in tracked files.
- Commit identity sanitized to GitHub `noreply` email.

## Local Preview
```bash
python3 -m http.server 8080
```
Then open `http://localhost:8080`

## Project Files
- `index.html`: app page
- `manifest.webmanifest`: PWA manifest
- `sw.js`: service worker
