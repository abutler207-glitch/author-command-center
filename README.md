Author Command Center v30 — Backup Naming + Receipt Preview

What's new:
- Backup export filenames now include app version and export date.
  Example: Author_Command_Center_Backup_v30_2026-06-03.zip
- Restore JSON export filenames now include app version and export date.
  Example: Author_Command_Center_Restore_v30_2026-06-03.json
- Receipt Vault now has a Preview button for attached receipts.
- Image receipts open in a larger preview modal.
- PDF receipts attempt to open in an embedded preview with Open/Save fallback.
- Header shows v30 after deployment.

Deploy:
1. Upload/overwrite all files in your GitHub repository with this folder's contents.
2. Commit changes.
3. Open your GitHub Pages URL with ?v=30:
   https://YOURUSERNAME.github.io/author-command-center/?v=30

If your phone still shows the old backup filename or no receipt preview:
- Delete the old Home Screen icon.
- Open the ?v=30 URL.
- Add the ?v=30 page to Home Screen again.
