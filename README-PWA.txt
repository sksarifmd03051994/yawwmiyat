YAWMIYAT PWA PACKAGE

This is a Progressive Web App (PWA) package, not an APK.

To install on Android:
1. Upload the contents of this folder to an HTTPS static host (for example GitHub Pages or Netlify). Keep index.html, manifest.webmanifest, sw.js, and both icons in the same folder.
2. Open the published HTTPS address in Chrome on Android.
3. Tap Chrome menu (⋮) > Install app (or Add to Home screen).
4. Confirm. Yawmiyat will appear on the Android Home Screen and open in standalone app mode.

Important:
- PWA installation does NOT work by opening index.html from Downloads/file://. It must be served over HTTPS (localhost is the development exception).
- User records and PIN are still stored locally in that browser profile using localStorage. This package does not provide cloud backup or encryption. Export the monthly PDF regularly and do not clear site data.
- Hind Siliguri loads from Google Fonts when internet is available; it falls back to sans-serif when offline.
