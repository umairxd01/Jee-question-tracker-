JEE Question Tracker — installable PWA

Files:
- index.html — app
- manifest.webmanifest — PWA install metadata
- sw.js — offline app shell/service worker
- icons/ — install/app icons

Install:
1. Host this folder on HTTPS (GitHub Pages works).
2. Open the deployed index.html in Chrome on Android.
3. Use the browser menu and choose “Install app” / “Add to Home screen”.

Data:
Question data is stored locally in the browser using localStorage.
Use Backup / Export regularly to keep a portable JSON backup.
