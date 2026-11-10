WAKE UP PRO - ANDROID INSTALLABLE PWA

FILES
- index.html: complete app
- manifest.json: Android install metadata
- sw.js: offline app shell
- icon-192.png and icon-512.png: app icons

HOW TO INSTALL ON ANDROID
1. Upload all files to an HTTPS host (for example, your own GitHub Pages site).
2. Open the hosted HTTPS address in Chrome on Android.
3. Open Chrome's three-dot menu.
4. Choose "Install app" or "Add to Home screen".
5. Open Wake Up Pro from the home screen.

IMPORTANT LIMITATIONS
- This is an installable PWA, not a native APK.
- The alarm voice repeats continuously until dismissed while the app is running. Browser speech/alarm timers are not guaranteed when Chrome is closed, the phone is locked for a long time, battery saver is active, or Android suspends the app.
- For a reliable alarm, also set the same time in Android's built-in Clock app.
- The app asks Android/browser for a Hindi voice and prefers voice names that appear male. Browser speech APIs do not provide a reliable gender or hoarseness control. Voice availability depends on the phone and installed speech services.
- Notifications and speech reminders require permissions and may behave differently by device.
