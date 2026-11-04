WASATCH INSPECTOR V1 — QUICK START

Contents:
- index.html: the inspection application
- manifest.webmanifest: installable app metadata
- sw.js: offline app-shell cache
- README.txt: these instructions

IMPORTANT LIMITATIONS
1. Inspection records and photos are stored locally in the browser's IndexedDB on the device. They are not synced to another device.
2. Export a JSON backup after every inspection day and before clearing browser data, changing phones, or reinstalling.
3. Offline app-shell caching requires the app to be opened at least once online from a secure HTTPS website. A file opened directly from Files may run locally, but service-worker offline installation will not work.
4. For iPhone installation, publish the folder to a free HTTPS static host (for example GitHub Pages or Netlify), open its URL in Safari while online, tap Share > Add to Home Screen, then open the installed app once online. After it has loaded, test airplane mode.
5. iOS may evict website data under storage pressure. This local-only version is not a substitute for a managed backup system.
6. The report is an operational template, not legal advice or a mechanical certification. Have your scope, disclaimers, business practices, and insurance reviewed for your circumstances.

FIRST TEST
- Create a test inspection using a sample vehicle.
- Add statuses and notes, add a photo, save.
- Generate report and use Print > Save as PDF.
- Return to dashboard and reopen the inspection.
- Export a backup JSON.
- Restore that JSON in a test browser profile if possible.

No account, paid subscription, or cloud database is required for this prototype.
