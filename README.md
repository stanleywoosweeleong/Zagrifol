# Zagrifol 选用指南 · Zagrifol Finder · Panduan Zagrifol

Offline-first product finder (中文 / English / Malay) compiled from the printed
ZAGRIFOL leaflet of Zagro Chemicals Sdn Bhd. Not an official Zagro app.

Live: https://stanleywoosweeleong.github.io/Zagrifol/

## Files

- `index.html` – the whole app (text, logic, photos and QR code inlined)
- `sw.js` – self-updating service worker (fixed cache name, nothing to bump)
- `manifest.json`, `icon-180/192/512.png` – install metadata and text-free icon
- `og.jpg` – WhatsApp / social link preview

## Updating

Edit `index.html` and push. There is no version number to bump: installed
copies open instantly from cache, check for changes on launch, and show a
"new version is ready" bar. GitHub Pages takes a minute or two to publish.

## Content rules

- The leaflet prints no dose rates, so the app gives none and points to the bottle label.
- Product effects are the leaflet's own statements.
