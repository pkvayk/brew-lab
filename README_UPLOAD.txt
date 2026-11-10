MY BREW LAB v1.4.5 — GitHub Pages upload (flat, same layout as your repo)
Replace these 5 files in the root of your repo (folder 'assets' can stay as it is):
  index.html   sw.js   manifest.webmanifest   icon-192.png   icon-512.png
1) Upload to branch 'stable' first -> test the Pages URL -> then open a Pull Request stable -> main and merge.
2) After deploy: open the app, fully close it, open again (the service worker swaps to the new version).
3) Your data stays (same address = same browser storage). Export a JSON backup first anyway.
