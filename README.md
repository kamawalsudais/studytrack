# StudyTrack

A mobile-friendly assignment tracker that works as a Progressive Web App (PWA).

## Features
- Add assignments with class, due date, priority, type and notes
- Mark work complete and see what remains
- Progress bar and task totals
- Search, filter (to do, completed, upcoming, overdue) and sort
- Edit or delete assignments
- Saves data in the browser on the device
- Installable on phones and caches the app shell for offline use

## Put it on GitHub
1. Create a new GitHub repository, for example `studytrack`.
2. Upload `index.html`, `manifest.json`, `sw.js`, `icon.svg` and this README to the repository's root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Open the published HTTPS URL.

## Install it on your phone
- **iPhone:** Open the GitHub Pages URL in Safari → Share → Add to Home Screen.
- **Android:** Open the URL in Chrome → menu (⋮) → Install app or Add to Home screen.

## Important data note
Assignments are stored locally in the browser using localStorage. They do not automatically sync between devices and may be lost if browser site data is cleared. Export/backup and account-based sync are not included in this starter version.

## Customizing
Edit the colors in the `:root` section near the top of `index.html`.
