# LWH Tag Generator PWA v1.1

This package is ready for GitHub Pages and should trigger Chrome/Edge install once published over HTTPS.

## Files included
- `index.html`
- `manifest.json`
- `service-worker.js`
- `icons/icon-192.png`
- `icons/icon-512.png`

## Upload to GitHub
Upload the contents of this folder to the repo root:

`https://github.com/nbr1hawgfan/LWH_Tag_Generator`

Then open:

`https://nbr1hawgfan.github.io/LWH_Tag_Generator/`

## Install tips
After uploading, open the site and hard refresh once:

Windows Chrome/Edge: `Ctrl + Shift + R`

Then wait 10–30 seconds. The install icon usually appears in the address bar, or under the browser menu as **Install app**.

## Important fix in v1.1
The service worker now pre-caches only local files. External CDN scripts are cached only after they load successfully. This makes the service worker install much more reliable on GitHub Pages.
