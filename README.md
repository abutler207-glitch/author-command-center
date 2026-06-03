# Author Command Center — GitHub Ready Blank Version

This package is safe to upload to a public GitHub Pages repository.

## What is included

- `index.html` — the app
- `manifest.webmanifest` — home-screen app settings
- `service-worker.js` — offline cache support
- `.nojekyll` — tells GitHub Pages to serve the files normally
- `icons/` — iPhone/home-screen app icons

## Important privacy note

This GitHub-ready app is blank by default. Do not upload your private data import JSON, receipt backups, tax exports, or Google Drive backup ZIPs to a public GitHub repository.

Your private author data is stored locally in your browser and in whatever backup ZIP/JSON files you export.

## GitHub Pages setup

1. Create a free GitHub account.
2. Create a public repository named `author-command-center`.
3. Upload the contents of this folder, not the folder itself.
4. Go to repository **Settings > Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.
7. Wait a few minutes for GitHub to publish the site.
8. Open the GitHub Pages URL on your iPhone.

## Add to iPhone Home Screen

1. Open the GitHub Pages link in Safari or Chrome.
2. Tap the Share icon.
3. Choose **Add to Home Screen**.
4. Name it `Author Command Center`.
5. Tap **Add**.

## Import your private data file

After the app opens:
1. Go to **Backup**.
2. Tap **Import Restore JSON**.
3. Select your private import JSON file.
4. The dashboard should fill with your books, tasks, expenses, and settings.

## Weekly backup habit

1. Update the app.
2. Go to **Backup**.
3. Tap **Share / Save Google Drive Backup ZIP**.
4. Save the ZIP to Google Drive: `Author Business / Backups`.


## Custom series names

The app starts with generic series labels so the public code does not include private project names. After importing your private JSON file, your actual series names will display in the app.
