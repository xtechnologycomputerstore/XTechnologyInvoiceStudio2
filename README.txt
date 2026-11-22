X TECHNOLOGY INVOICE STUDIO V8.58 — PWA PACKAGE

Files:
- index.html: your Invoice Studio V8.58, with PWA support added
- manifest.webmanifest: install identity and app display settings
- service-worker.js: offline caching
- icons/: app icons

IMPORTANT: PWA installation requires hosting on HTTPS (or localhost). Opening index.html directly from your phone's Downloads will not enable installation/offline service worker.

Recommended free hosting using GitHub Pages:
1. Create a GitHub repository (Public is easiest for Pages).
2. Upload all files/folders in this package (index.html, manifest.webmanifest, service-worker.js, icons).
3. Repository Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Wait for the Pages URL to appear, then open it in Android Chrome.
5. Chrome ⋮ menu → Install app / Add to Home screen.

App data is stored in the browser on the device as in the original HTML. Use the built-in JSON Backup regularly. Hosting this PWA does NOT automatically sync data between devices.
