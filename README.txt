FIT FIRE Android/PWA starter

This is a PWA-ready web package, not an APK file. It must be uploaded to an HTTPS host before Android can install it reliably. The game loads Three.js from jsDelivr, so the first version requires internet.

PHONE-ONLY ROUTE (GitHub Pages):
1. Sign in/create an account on GitHub in Chrome. Create a public repository named fit-fire-game.
2. Upload all five files from this ZIP's folder root: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.
3. In repository Settings -> Pages, choose Deploy from a branch, branch main, folder /(root), then Save. Wait for the published HTTPS URL.
4. Open that URL in Chrome on Android -> menu ⋮ -> Install app or Add to Home screen. The exact wording varies.
5. To produce an APK, use PWABuilder (https://www.pwabuilder.com/) with the published HTTPS URL and follow its Android package/signing flow. APK generation and signing depend on the service's current workflow.

CONTROLS: The current prototype's mobile buttons are limited; this is not a finished mobile game. A true standalone APK with native performance, production assets, full touchscreen aiming and online multiplayer requires further development and testing.
