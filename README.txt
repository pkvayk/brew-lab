MY BREW LAB v1.0 — INSTALLATION

The app is a static PWA using IndexedDB for local data. No backend or account is required.

DEPLOY (recommended for iPad):
1. Extract this ZIP in the Files app on iPad.
2. Upload the complete folder's contents to any static HTTPS host (for example Netlify Drop, Cloudflare Pages, GitHub Pages).
3. Open the published HTTPS address in Safari on iPad.
4. Tap Share > Add to Home Screen > Add.
5. Open My Brew Lab from Home Screen. Once loaded, the service worker caches app files for offline use.

IMPORTANT: Opening index.html directly from the Files app is not the supported installation path; HTTPS hosting is needed for a reliable PWA and service worker.

DATA:
- IndexedDB data lives on the device and browser origin. It does NOT sync across devices.
- Export JSON backups and save them to iCloud Drive regularly.
- Import JSON merges records by ID.
- CSV export is for spreadsheets and not a full backup.
- Clearing Safari website data may erase your records.
- The three historical sample brews are approximations from prior user-provided notes. Check and edit their dates, details and ratings; ratings are illustrative.


Version 1.2.0: Recipe Library, conditional equipment settings, tasting radar sliders. Database schema version 4; back up before updating.
