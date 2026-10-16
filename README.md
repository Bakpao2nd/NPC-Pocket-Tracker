# Beyblade X Launch Lab v6 — Offline PWA

1. Export a JSON backup from your existing Launch Lab before updating.
2. Extract this ZIP and upload **all files and the technique-images folder** into the root of your GitHub Pages repository, replacing index.html, sw.js, and manifest.webmanifest.
3. Wait for the Pages deployment, open the website online, then close and reopen to confirm the updated v6.
4. Install/Add to Home Screen and test Airplane Mode. The service worker caches all 20 diagrams for offline use.
5. Existing data uses the same localStorage key and backup schema as v5. Legacy custom techniques remain readable but can be replaced with a preset.

### Note on angles
The PDF establishes names and intended movement. Tilt-degree ranges are experimental coaching starting points inferred from community launch guidance, not documented measurements for these exact cards. Calibrate by bit, stadium and spin.

### Troubleshooting
If an old version persists, refresh online and close/reopen the installed app. Avoid clearing browser data unless you have exported a backup.
