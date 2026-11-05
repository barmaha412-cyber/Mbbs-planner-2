FINAL YEAR MBBS PLANNER — INSTALL FIX

This bundle adds the standard PWA icons and updates the manifest and service worker.

Upload/replace these files in the ROOT of your existing GitHub repository:
- index.html (same planner as before; keep or re-upload)
- manifest.webmanifest (replace existing)
- sw.js (replace existing)
- icon-192.png (new)
- icon-512.png (new)

Then:
1. Commit the changes to the main branch.
2. Wait for GitHub Pages to publish.
3. Open the HTTPS Pages URL in Chrome.
4. Refresh the site, close any old tab for it, and reopen it.
5. If Chrome still says it cannot install, clear this site's cached data/service worker and revisit. Use Chrome > Site settings > Storage / Clear data for this site, then reload.

The app's checklist data is stored in browser localStorage. Export a backup from the app before clearing site data.
