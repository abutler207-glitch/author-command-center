Author Command Center v13 — Home Button Replacement Fix

What's fixed:
- The top toolbar now truly replaces Export JSON with 🏠 Home.
- Home returns to Dashboard and scrolls to the top.
- A delegated click handler was added so the Home button works even on mobile browsers.
- Backup/export remains available through the Backup tab and Drive Backup button.

Deploy:
1. Upload/overwrite all files in your GitHub repository with this folder's contents.
2. Commit changes.
3. Open your GitHub Pages URL with ?v=13:
   https://YOURUSERNAME.github.io/author-command-center/?v=13

If your phone still shows Export JSON:
- Confirm your GitHub index.html says v13.
- Open the ?v=13 URL directly.
- Delete the old Home Screen icon and re-add the ?v=13 page.
