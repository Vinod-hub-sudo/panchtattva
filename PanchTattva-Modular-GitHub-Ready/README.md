# PanchTattva

Modular Progressive Web App (PWA) for World Clock, Solar & Night Arc Tracking, Drik Ganita Panchangam, Jyothishyam & Kundali, Sacred Temples, Local Sightseeing, and Festivals.

## Repository Layout
- `index.html` — App shell and 6-tab UI
- `css/app.css` — Styling and solar/lunar arc rules
- `js/app.js` — Clocks, night/lunar tracker, Panchangam, Kundali, temples, sightseeing, and festivals logic
- `data/temples.json`, `data/corridor-trains.json`, `data/corridor-buses.json` — Structured datasets
- `.github/workflows/deploy.yml` — Automated file/JSON validation and GitHub Pages deployment

## GitHub Pages Setup
1. Push all files to the `main` branch.
2. In GitHub, go to **Settings -> Pages -> Build and deployment**, set **Source** to **GitHub Actions** (or **Deploy from a branch** on `main` / `/(root)`).
