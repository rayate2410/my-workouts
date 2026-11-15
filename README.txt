12-Week Recomp Log (offline Android app)

Put these 6 files in one folder on any HTTPS host, for example GitHub Pages:
  index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, icon-maskable-512.png

Then open the page URL once in Chrome on your Android phone:
  menu (three dots) > Install app (or Add to Home screen).
After the first load it works fully offline. Data is saved on the phone.

Backup: tap "Export data" at the bottom of the app and attach the .json file in chat for a review.
Restore: tap "Import" and pick that file.

If you change index.html later, change CACHE = "recomp-log-v1" in sw.js to v2 so phones update.
