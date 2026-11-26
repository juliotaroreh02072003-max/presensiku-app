PRESENSIKU — PWA starter
========================

This package is a lightweight installable-web-app wrapper around your existing Google Sites page.

Files:
- index.html: app wrapper
- manifest.json: app identity/install settings
- sw.js: basic shell caching
- icons/: app icons

IMPORTANT:
This package is not yet hosted. It must be uploaded to a hosting service that serves files over HTTPS (for example GitHub Pages or Netlify).
The Google Sites content is embedded in an iframe. If Google Sites blocks framing or some features (login, geolocation, forms) do not behave correctly inside the iframe, this wrapper may not work as intended; in that case use a direct-link approach or redesign the app frontend.

Target site:
https://sites.google.com/view/presensiku-sistem-kehadiran-ka/full-page-embed

Basic setup:
1. Upload the contents of this folder to a static HTTPS host.
2. Open the hosted URL in Chrome on Android.
3. Use Chrome menu > Install app / Add to Home screen, if offered.
