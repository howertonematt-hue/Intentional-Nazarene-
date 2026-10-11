# Intentional Nazarene — Joplin First

A zero-cost, static, mobile-friendly discipleship web app. No login, backend, analytics, or external JavaScript dependencies.

## Features
- Nine complete introductory lessons, Scriptures, reflection prompts, class discussion, and practical steps
- Browser-local autosave, completion tracking, backup and restore
- Print blank workbook, completed workbook, or current chapter (browser print dialog; choose Save as PDF if desired)
- Class discussion toggle

## Publish free using GitHub Pages
1. Create a free GitHub account at https://github.com.
2. Create a **public** repository named `intentional-nazarene`.
3. Upload `index.html`, `app.js`, `manifest.webmanifest`, and `.nojekyll` to the **repository root** (not a nested folder). Do not upload private workbook backups.
4. Open repository **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**, and Save.
5. Once published, the address should be `https://YOUR-USERNAME.github.io/intentional-nazarene/`. Allow a few minutes.
6. Open the address on a phone or computer. Use the browser menu to add to the home screen if supported.

## Local test
Open `index.html` in a browser. For a more representative local test, from this directory run `python -m http.server 8000` and visit http://localhost:8000.

## Privacy and limitations
- Reflections are stored in the current browser's localStorage, not on a server. They are not synchronized between devices or accounts.
- Private/incognito browsing or clearing site data can erase progress. Export a backup regularly.
- JSON backups contain sensitive reflections in plain text; store and share them carefully.
- Browser print options control PDF output. This is not a server-generated PDF.
- App is an educational draft; review doctrinal and Joplin First-specific content with church leadership before public distribution.
- Official Manual content is linked, not reproduced. Confirm permissions before republishing copyrighted material.
- No church membership status is conferred or recorded by this app.

## Sources
- https://nazarene.org/manual
- https://nazarene.org/resources/articles-of-faith/
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
