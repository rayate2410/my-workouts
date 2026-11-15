LogMyWorkouots (offline workout planner and logger)

Put these 6 files in one folder on any HTTPS host, for example GitHub Pages:
  index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, icon-maskable-512.png

Then open the page URL once in Chrome on your Android phone:
  menu (three dots) > Install app (or Add to Home screen).
After the first load it works fully offline. Data is saved on the phone.

Use Previous/Next or the week strip to navigate. Create, edit, or delete a workout on an individual date; changes do not affect other days.

Backup: tap "Export data" at the bottom of the app. Restore: tap "Import" and pick an exported .json file.

If you change index.html later, bump the CACHE value in sw.js so installed apps download the new version.
