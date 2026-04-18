# The Wheel — Edina CC Golf App

A Progressive Web App (PWA) for tracking The Wheel and 9 Point Game at Edina Country Club.

## Games included
- **The Wheel** (5 players): 3 two-on-two matches, 5·5·5 betting, Greenies, auto-press
- **9 Point Game** (3 players): Independent player setup, net scoring, $1–$3/pt with presses, Greenies

## Deploy to GitHub Pages (free hosting)

1. Create a new GitHub repository named e.g. `the-wheel`
2. Upload all files in this zip to the repo root
3. Go to **Settings → Pages → Source → main branch → / (root)** → Save
4. Your app will be live at `https://yourusername.github.io/the-wheel/`

## Install on iPhone

1. Open the GitHub Pages URL in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add** — it appears as a full-screen app icon

## Files
- `index.html` — entire app (all games, scoring, presses, money, greenies)
- `manifest.json` — PWA metadata for home screen install
- `sw.js` — service worker for offline play on the course
- `icon-192.png` / `icon-512.png` — home screen icons
- `README.md` — this file

## Works fully offline
Once loaded in Safari, the app works with no cell signal — perfect for the course.
