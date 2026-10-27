# The Pocket Journal

A notebook-style journal for quick notes, with journals, folders, rich formatting and photos.
Your notes are saved only on the device you use it on.

## Put it on GitHub Pages

1. Sign in at github.com (or make a free account).
2. Click **New repository**. Name it `pocket-journal`, choose **Public**, and click **Create repository**.
3. Click **uploading an existing file**, drag in everything from this folder
   (`index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder), then click **Commit changes**.
4. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**,
   pick **main** and **/ (root)**, and click **Save**.
5. Wait a minute or two. Your app will be at `https://YOUR-USERNAME.github.io/pocket-journal/`.

## Add it to your phone

- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.
- **Android (Chrome):** open the link, tap **⋮**, then **Install app** or **Add to Home screen**.

Once it's on your home screen it opens full screen and works without internet.

## Move your notes over

1. In the old version, go to **Settings → Back up → Export all journals** and save the file.
2. Get that file onto your phone (AirDrop, email, Files, iCloud Drive).
3. In the new app, go to **Settings → Import notes → From a Pocket Journal export** and choose the file.

## Keep your notes safe

Notes live in the browser storage of the app on that device. Clearing website data for the site
erases them, so use **Export all journals** now and then as a backup.

## Updating the app later

Upload the new `index.html` over the old one, and change `VERSION` at the top of `sw.js`
(for example to `pocket-journal-v2`) so phones pick up the new version.

## Notes

- The ✨ Ask Claude menu only works inside claude.ai, so it's hidden here.
- Fonts and the Day One zip reader load from the internet the first time, then work offline.
