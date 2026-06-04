Author Command Center v25 — Campaign Form Load Fix

What's fixed:
- Add Campaign now loads the campaign form inside the modal.
- Removed an accidental campaign hook that was placed in the metric updater instead of the main modal handler.
- Added a visible fallback message if any modal form fails to load.
- Modal scrolling/visibility improved for iPhone.
- Header shows v25 after deployment.

Deploy:
1. Upload/overwrite all files in your GitHub repository with this folder's contents.
2. Commit changes.
3. Open your GitHub Pages URL with ?v=25:
   https://YOURUSERNAME.github.io/author-command-center/?v=25

If your phone still shows the blank campaign modal:
- Delete the old Home Screen icon.
- Open the ?v=25 URL.
- Add the ?v=25 page to Home Screen again.
