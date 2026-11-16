PACKWISE PWA — INSTALLATION

1. Extract this ZIP.
2. Create a public GitHub repository (e.g. packwise).
3. Upload index.html, manifest.webmanifest, sw.js and the icons folder, preserving paths.
4. In GitHub Settings > Pages, set Deploy from a branch, main, /(root), then Save.
5. Wait for the Pages URL (https://YOURNAME.github.io/packwise/).
6. Open that URL in Chrome on Android > three-dot menu > Install app or Add to Home screen.

The app works offline after the first successful visit. Trip data stays in the browser storage on that device and is not synced. Opening the hosted PWA uses different storage from the old downloaded HTML file, so existing saved trips do not migrate automatically. Keep your old file until you have copied any lists you need.

For updates, upload revised files and change CACHE version in sw.js.
