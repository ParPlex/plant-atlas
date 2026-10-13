# Plant Atlas

A personal world map with a dot for every plant visited. Installable web app (PWA):
open it on a phone, add it to the home screen, and it works offline.

- Plants are stored on the device only (browser storage). Use Export / Import in the app for backups.
- Place lookup sends only the typed city text to OpenStreetMap Nominatim; plant names never leave the device.
- No build step. Static files, hosted on GitHub Pages.

When changing files, bump `VERSION` in `sw.js` so installed copies pick up the update.
