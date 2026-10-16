# Beyblade X Launch Lab v5 — Offline PWA

## Deploy with GitHub Pages
1. Create a **public** GitHub repository, e.g. `beyblade-launch-lab`.
2. Upload the **contents of this folder** to the root of the repository (not the folder itself).
3. In **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)`, then Save.
4. Wait for GitHub to publish, then visit `https://YOUR_USERNAME.github.io/beyblade-launch-lab/`.
5. Open once while online, then test offline using airplane mode. iPhone: Safari → Share → Add to Home Screen. Android: Chrome → menu → Install app/Add to Home screen.

## Storage and backups
Data is stored per browser/device using the existing v4 storage key; there is no automatic cross-device synchronization. Use the built-in Export/Import JSON backup feature. If your earlier version was opened from a `file://` URL, its data may not automatically appear on the hosted site: export from the old version and import into the new website.

## Updating
Replace `index.html` and related files in GitHub. When changing the offline asset set or requiring a fresh cache, update the CACHE_NAME string in `sw.js`. Users should open the website while online to pick up updates. Cached content and local data can be removed by the browser or OS.

## Privacy
The app has no backend and does not upload your training data. The website source is public on GitHub Pages. This is a fan-made personal training tracker, not affiliated with Beyblade/Takara Tomy/Hasbro.
