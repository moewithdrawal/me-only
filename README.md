# Little Wish — Applewood Village (iPhone PWA)

This version keeps the main dashboard simple and practical, with the storybook fantasy world available as an optional Explore area. It is a static HTML/CSS/JavaScript app designed for iPhone Safari and GitHub Pages.

## What's included
- Simple home dashboard with companion greeting, daily overview shortcuts, little quests, rotating wishes, and custom shortcuts.
- Persistent bottom navigation: Home, Planner, Care, Journal, More/Explore.
- Optional Applewood Village story page with location links into the practical sections.
- Existing starter features retained: manual transactions, savings goals, personal goals, recipes with optional photos, journal entries, companion name and expression PNG uploads, themes, custom colors, and JSON backup/restore.
- A basic noticeboard for personal plans and a small offline-friendly care prompt area.
- Service worker cache for offline reopening after the first successful visit.

## Update an existing GitHub Pages app
1. Before replacing anything, open your current Little Wish app and go to **More → Settings & themes → Backup & restore → Export backup**. Save that JSON file somewhere safe.
2. Download and unzip `little-wish-applewood-v2.zip` on your iPhone (Files app).
3. Open your GitHub repository in Safari and choose **Add file → Upload files**.
4. Upload/replace `index.html`, `manifest.webmanifest`, and `sw.js` from the unzipped folder. Commit the changes.
5. Reopen the published app in Safari. If the old screen remains, close the app, open the website in Safari, and refresh. The service worker cache name has changed to prompt an update.
6. Your existing app data uses the same localStorage key and should remain on that browser installation. Still keep the backup from step 1 before updating.

## Important limitations
- Data is stored locally on this device/browser. There is no account or cloud sync. Export backups regularly.
- This is an incremental visual/navigation update, not yet the complete feature roadmap. Full calendar scheduling, recurring bills, advanced wellness logs/graphs, recipe-to-grocery automation, and story chapters are not implemented yet.
- The wellness area is a gentle check-in and grounding prompt starter, not medical advice or a substitute for your dietitian's instructions.
- Scheduled notifications are not implemented. iOS web push requires additional setup and support testing.
- Keep personal backup JSON files private. Do not upload backups to a public GitHub repository.
