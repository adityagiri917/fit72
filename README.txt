GymTrack Complete Local PWA

This folder contains the complete GymTrack app.

Files:
- index.html = main app webpage
- manifest.json = install/app metadata
- service-worker.js = offline cache support
- icons/ = app icons

To test on your computer:
1. Unzip this folder.
2. Open index.html in your browser.

For proper install/offline PWA behavior:
- Use HTTPS hosting or localhost.
- Opening index.html directly works for basic use, but service worker/PWA install may not fully work from file://.

Your data:
- Saved locally in the browser using localStorage.
- Export backups regularly from More > Backup / Restore.

Update: This version includes customizable profile/goal settings for start weight, current weight, target weight, and height.

This version removes fixed 72 kg branding and uses customizable profile/goal settings.
