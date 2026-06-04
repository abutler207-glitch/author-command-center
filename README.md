Author Command Center v31 — Multi-Page PDF Receipt Preview

What's new:
- PDF receipt preview now attempts to render every page, not just the first page.
- Multi-page PDFs display as scrollable page canvases inside the preview modal.
- Image receipt preview still works as before.
- Open/Save remains as fallback if the browser cannot render the PDF.
- Backup filenames still include app version and export date.
- Header shows v31 after deployment.

Note:
- Multi-page PDF preview uses PDF.js from a CDN, so it needs internet access the first time it loads.
- If a PDF is very large, rendering may take a few seconds on phone.

Deploy:
1. Upload/overwrite all files in your GitHub repository with this folder's contents.
2. Commit changes.
3. Open your GitHub Pages URL with ?v=31:
   https://YOURUSERNAME.github.io/author-command-center/?v=31

If your phone still shows the old receipt preview:
- Delete the old Home Screen icon.
- Open the ?v=31 URL.
- Add the ?v=31 page to Home Screen again.
