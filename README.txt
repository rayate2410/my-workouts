MyWorkouts (offline workout planner and logger)

Put these 6 files in one folder on any HTTPS host, for example GitHub Pages:
  index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, icon-maskable-512.png

Then open the page URL once in Chrome on your Android phone:
  menu (three dots) > Install app (or Add to Home screen).
After the first load it works fully offline. Data is saved on the phone.

The app opens on today's workout. Use the previous/next day arrows to navigate, or "Go to today" to return. The Streaks card shows this week's dates and opens a monthly calendar; select a month and tap a date to open its log. A date counts as done when every planned activity is completed. Open the three-line menu for Today's workout, Workout library, Weekly schedule, and Backup. Create reusable workouts and exercises in Workout library, then assign one saved workout to each weekday in Weekly schedule. The schedule repeats every week. To customize a particular date, edit that day's workout to add exercises from one or more saved workouts, choose existing exercises, or create new ones. Use the edit icon on a date to make a one-day alternate, restore its scheduled workout, or remove that day's workout. Set exercises, reps, and tracking units separately; select kg/lb, km/mi, minutes/seconds, bodyweight, or no value.

In Backup, tap "Export data" to save a copy. Restore: tap "Import" and pick an exported .json file. Google Drive backup and restore are manual. Set `CLIENT_ID` near the top of the app script to a Google OAuth web client ID and configure this app's deployed origin in Google Cloud. Drive access uses the `drive.file` scope, which limits access to files created or opened by this app.

If you change index.html later, bump the CACHE value in sw.js so installed apps download the new version.
