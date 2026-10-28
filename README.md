# Ajay Personal Academic Planner — PWA v5

This version is ready for GitHub Pages and can be installed on Android like an app.

## Publish from your phone
1. Sign in to github.com in Chrome.
2. Create a new public repository, for example: `ajay-academic-planner`.
3. Open the repo → Add file → Upload files.
4. Upload ALL of these at the repository root:
   - index.html
   - manifest.webmanifest
   - service-worker.js
   - icons/icon-192.png
   - icons/icon-512.png
5. Commit the files.
6. Open repository Settings → Pages.
7. Under Build and deployment choose:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /(root)
8. Save.
9. Open the GitHub Pages URL in Chrome on Android.
10. Tap the site's Install app button, or Chrome ⋮ → Add to Home screen / Install app.

## Important
- Planner data is stored in localStorage on that browser/device.
- Export a backup from Settings before clearing browser data or changing phones.
- The PWA shell works offline after the first successful online load.
