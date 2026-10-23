# GhostData website

Public information site for GhostData, a local Hearthstone Standard tracker in development.

Website: https://loyallambchops.github.io/ghostdata-site/

This repository contains only website HTML, CSS, JavaScript and approved product imagery. The application source remains in its separate repository. No application downloads, personal match history, private media kit or credentials are stored here.

## Maintain

Edit `index.html`, `development.html` or `privacy.html` directly. Shared presentation is in `styles.css` and `site.js`. There are no build dependencies. Push to `main`; GitHub Pages publishes from the repository root. Keep `.nojekyll`.

Preview with `python -m http.server 8765 --bind 127.0.0.1`, then open http://127.0.0.1:8765/.

Before publishing: verify mobile layout and keyboard navigation; check links and images; keep release status and screenshot sample labels accurate. Never copy the application checkout or local match data into this repository.

Developed by LoyalLambChops · LoyalLambChops@gmail.com
