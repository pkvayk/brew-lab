MY BREW LAB v1.4.8 — GitHub Pages upload
A) App files (replace in the ROOT of the repo, branch stable-setup first):
   index.html   sw.js   manifest.webmanifest   icon-192.png   icon-512.png
B) Optional automatic checks (see chat for the iPhone steps). Create these two files with Add file > Create new file:
   tools/check.js                (replace it if it exists: the new version has more tests)
   .github/workflows/ci.yml      (only once; unchanged)
C) Test on stable-setup, then Pull Request -> main -> Merge. Close and reopen the app twice after deploy.
