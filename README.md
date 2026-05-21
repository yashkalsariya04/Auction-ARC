# AuctionArc

A simple static auction website built with HTML, CSS and JavaScript. This repository contains the frontend files for AuctionArc (no backend included). It uses Firebase client code located in `jsfiles/firebase-config.js` for optional features like authentication and database access.

## Quick start

- Serve locally from the project root (requires Python 3):

```bash
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

- Or open `index.html` directly in your browser for basic viewing.

## Files of interest

- `index.html` — main landing page
- `cssfiles/` — stylesheets
- `jsfiles/` — JavaScript code (including `firebase-config.js`)

## Deploy

- GitHub Pages: enable Pages in repo settings and select the `main` branch (root).
- Firebase Hosting: configure Firebase Hosting if you want a production-ready deploy.

## Notes

- If you use Firebase features, ensure you set correct Firebase config in `jsfiles/firebase-config.js` and enable the required services in your Firebase console.

Enjoy!
