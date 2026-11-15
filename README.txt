LogMyWorkouts (offline workout planner and logger)

Put these 6 files in one folder on any HTTPS host, for example GitHub Pages:
  index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, icon-maskable-512.png

Then open the page URL once in Chrome on your Android phone:
  menu (three dots) > Install app (or Add to Home screen).
After the first load it works fully offline. Data is saved on the phone.

The app opens on today's activity. Use the previous/next day arrows to navigate, or "Go to today" to return. Open Plans to create reusable weekday workouts that appear in future weeks. Use the edit icon on a date to make a one-day alternate, restore its weekday plan, or remove that day's workout. Exercise names, sets, reps, and tracking units have separate fields; select kg/lb, km/mi, minutes/seconds, bodyweight, or no value, and use "+ Add exercise" to add rows.

Backup: tap "Export data" at the bottom of the app. Restore: tap "Import" and pick an exported .json file.

If you change index.html later, bump the CACHE value in sw.js so installed apps download the new version.
