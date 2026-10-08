# Item Stock Manager V25

اردو RTL Fabric Stock Manager V25.

## Included
- Original V25 HTML application.
- PWA manifest and offline service worker.
- Native Android WebView project.
- GitHub Actions workflow for debug APK.
- GitHub Pages workflow for the installable web app.

## Android APK
Pushes to `main` build a debug APK through GitHub Actions. The APK is published as the workflow artifact `ItemStockManagerV25-debug-apk`.

## Web App
When GitHub Pages is deployed, open the HTTPS Pages URL in Chrome/Edge and use **Install app / Add to Home screen**.

## Data
The V25 application keeps its operational data in browser/WebView local storage. Use the built-in Backup/Restore controls before changing devices.
