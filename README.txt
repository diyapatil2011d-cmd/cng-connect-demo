CNG CONNECT — PWA PACKAGE

FILES
- index.html: the app
- manifest.webmanifest: app name, icons and standalone display settings
- service-worker.js: caches the app shell for basic offline opening
- icons/: app icons

IMPORTANT PROTOTYPE LIMITATIONS
- Station records are sample/demo records.
- Owner role switching is a demonstration, not secure authentication.
- Data is stored in the current browser's local storage. Different phones do not share updates.
- Do not use the demo station status or waiting times for real travel decisions.
- This package is a PWA website, not a Google Play or Apple App Store submission.

HOSTING
1. Upload the CONTENTS of this folder to a static HTTPS host.
2. Keep index.html, manifest.webmanifest and service-worker.js in the same site root.
3. Keep the icons folder and its PNG files in the same relative path.
4. Open the HTTPS site on your phone.

ANDROID
- Open the site in Chrome.
- Use the browser menu and choose Install app / Add to Home screen.
- Confirm the install.

IPHONE
- Open the HTTPS site in Safari.
- Tap Share.
- Choose Add to Home Screen.
- Enable Open as Web App if shown, then tap Add.

PWA REQUIREMENTS
A manifest and HTTPS (or localhost for development) are needed for installability in supporting browsers.
Service workers provide app-shell caching; they do not make server-side data sync or live CNG data available offline.

For the NCSC demo, label all sample station information clearly as demonstration data.
