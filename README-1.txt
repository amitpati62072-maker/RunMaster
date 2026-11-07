RUN MASTER PWA

Files:
- index.html: Run Master app
- manifest.webmanifest: installable app metadata
- sw.js: service worker for app-shell offline support
- icons/: app icons

INSTALL / PUBLISH:
1. Upload the CONTENTS of this folder to a static web host that provides HTTPS.
2. Keep index.html, manifest.webmanifest, sw.js and icons/ in the same folder.
3. Open the HTTPS website in Chrome on Android.
4. Tap the browser menu (three dots) > Install app / Add to Home screen.
5. Open the installed Run Master icon.

IMPORTANT:
- PWA installation requires HTTPS (or localhost for testing); opening index.html as a local file is not enough.
- The app shell can open offline after the first successful visit, but map tiles need internet and GPS requires device location.
- Browser background execution is not guaranteed; keep the screen/browser active during runs for reliable tracking.
- This is a PWA package, not a native APK.
