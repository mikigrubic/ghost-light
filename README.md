# Ghost Light

Run lines on your phone. Ghost Light reads the other characters aloud, turns on your mic for your lines, and moves on when it hears your cue word. Say "line" to hear your next words.

## Put it online (GitHub Pages, about 5 minutes)

1. On github.com, create a new **public** repository, for example `ghost-light`.
2. Click **Add file → Upload files** and drag in every file from this folder:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` (and this README if you like). Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**. Save.
4. After a minute or two the page lives at `https://YOUR-USERNAME.github.io/ghost-light/`.

The page has to be served over https (GitHub Pages does this). Opening `index.html` straight from Files won't get mic access.

## Put it on your iPhone

1. Open the link in **Safari**.
2. Press **Start run** once. Allow the microphone and speech recognition when asked.
3. Tap **Share → Add to Home Screen**.

Then open it from the home-screen icon and run a scene. If you get a message that the mic is blocked from the icon, use the Safari tab instead. Some iOS versions don't allow speech recognition in home-screen apps. You can keep the Safari tab bookmarked or pinned.

## If something's off

- **Safari asks for the mic every time:** Settings → Apps → Safari → Microphone → Allow. Or in Safari, tap the "aA" button → Website Settings → Microphone → Allow.
- **"Tap to listen" keeps showing up:** iOS sometimes won't let a page restart the mic by itself. Tap the button and say your line. It still moves on when it hears your cue.
- **Reader goes quiet or plays through the earpiece after listening:** this is how iOS handles the mic and speaker sharing audio. Headphones (AirPods are fine) usually fix it.
- **Cue triggers too early:** set the cue to 2 or 3 words in Rehearsal settings.
- **Cue doesn't trigger:** say the last words clearly, or tap Done. Dictation has trouble with made-up names and old-fashioned language.
- **Better reader voices:** Settings → Accessibility → Spoken Content → Voices → English, then download an "Enhanced" or "Premium" voice. Choose it per character in Rehearsal settings.
- **Speech recognition needs internet** on most phones.

Scripts are saved in the browser you use. Safari and the home-screen icon may keep separate copies.

## Updating

Edit the files in the repo (or upload new ones). The app picks up changes the next time it opens online.
