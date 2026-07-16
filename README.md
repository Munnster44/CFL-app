# CFL 2026 Statistics Centre v3.3 GitHub Edition

A browser-based CFL schedule, score-entry, standings, power-ranking and prediction app.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload all files and folders from this package to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the **main** branch and **/(root)** folder, then click **Save**.
6. GitHub will display the website address after deployment.

## Updating the app

Replace the repository files with the newer versions and commit the changes. The service worker checks for updates. Users may need to reload once after an update is found.

## Saved scores

Scores and game edits are saved in the current browser using localStorage. They do not automatically synchronize between devices. Use **Export Scores to CSV** or **Export backup JSON** before changing devices or clearing browser data.

## Files

- `index.html` — complete application
- `manifest.json` — installable PWA settings
- `service-worker.js` — offline cache and update support
- `icons/` — application icons
