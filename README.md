# KalaChakra AI (v17)

A multi-tab web Progressive Web App (PWA) featuring:
- **World Clock & Solar Observatory**: Live clock, solar arc progression, sunrise/noon/sunset/daylight span, live city temperatures, and add/remove timezones.
- **Drik Ganita Panchangam**: Samvatsaram, Tithi, Nakshatram & Pada, Yogam, Karanam, Chandra Rashi, transition end times, Kala Vibhagam, and Tarabalam.
- **Jyothishyam & Kundali**: South Indian Rashi Kundali chart, Lagna & Navagraha positions, Janma Rashi, Nakshatra Pada, Gana, Nadi, Yoni, individual character/strengths analysis, Rashi Phalalu, and Vivaha Pontana.
- **Sacred Temples & Sightseeing**: Location-aware distance sorting, Live GPS + city selector + custom city search, live temperatures, local city transit for nearby temples, and train/bus guides for outstation shrines.
- **Festivals & Puranic Stories**: Calendar with religious vratams and national festivals (with day of week and tap-to-expand stories).

## Hosting on GitHub Pages
1. Create a new repository on GitHub (e.g., `kalachakra-ai`).
2. Extract all files (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `.gitignore`, `README.md`) into your repository folder so `index.html` is at the **root** of the branch.
3. Push to `main`:
   ```bash
   git init -b main
   git add .
   git commit -m "Deploy KalaChakra AI v17"
   git remote add origin https://github.com/<your-username>/kalachakra-ai.git
   git push -u origin main
   ```
4. On GitHub, go to **Settings → Pages → Build and deployment**, set **Source** to **Deploy from a branch**, select **`main`** and **`/(root)`**, and save. Your live HTTPS URL will be `https://<your-username>.github.io/kalachakra-ai/`.
