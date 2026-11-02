# Little Wish — Complete Applewood Village build

This update expands the existing iPhone PWA with: Buddy daily tasks and randomized dialogue; actual local calendar dates; financial calendar, bills and paycheck allocations; optional weight history graph; Care suggestions and grounding library; traditional 78-card tarot draws; recipes, meal planning and grocery lists; local PNG collectible asset bank and duplicate-allowing gachapon; low-energy mode; optional generated sound effects; local backup and restore.

## Install on GitHub Pages
1. Export a backup from the currently installed app before replacing files.
2. Extract this ZIP on your iPhone.
3. In your GitHub repository, replace `index.html`, `manifest.webmanifest`, and `sw.js` with the files from this folder and commit the changes.
4. Wait for GitHub Pages to finish publishing, then reopen the website. If the installed Home Screen app shows an old version, close it completely and open the site in Safari once.

## Storage and privacy
App data, uploaded PNGs, and custom companion art are stored in browser localStorage on this device. They are not uploaded to GitHub or synced automatically. Export backups regularly. PNG uploads are limited to 2 MB each in this build to reduce storage pressure. Avoid uploading personal backup JSON files to the public repository.

This is a client-side prototype. It does not include bank connections, cloud sync, push notifications, or guaranteed background alarms. Tarot is for reflection and entertainment, not financial or medical advice.
