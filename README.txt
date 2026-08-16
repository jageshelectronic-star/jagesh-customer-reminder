JAGESH ELECTRONIC FINAL V15

GPS update:
- Current Location uses the device Geolocation API directly from the user action.
- It requests a fresh high-accuracy fix and listens for multiple GPS readings, keeping the best accuracy.
- Address text is never converted into GPS coordinates.
- Android/browser location permission must be allowed by the user.

IMPORTANT: For reliable browser GPS, run the app from HTTPS (or localhost). Opening index.html directly from a ZIP/file:// can block or limit browser geolocation on Android/Chrome. A normal website/PWA install over HTTPS is recommended.

All existing project files/functions are retained from V14; only the GPS acquisition flow and this README were updated.
