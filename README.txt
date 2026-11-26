KR STORE — ANDROID APK BUILD PACKAGE

This project wraps https://krstoreglobal.netlify.app in an Android app.

BUILD AN INSTALLABLE APK USING GITHUB ACTIONS
1. Create a GitHub account if you do not already have one.
2. Create a NEW repository named KR-Store-App.
3. Upload the CONTENTS of this folder to the repository (keep the .github folder).
4. Open the repository's Actions tab.
5. Select "Build KR Store APK" and tap "Run workflow" (or wait for the first push build).
6. When the workflow finishes successfully, open that run and download the artifact named "KR-Store-Android-APK".
7. Extract the downloaded artifact ZIP. It contains app-debug.apk.
8. To install, open app-debug.apk on an Android phone and allow installation from that source if Android asks.

IMPORTANT
- The resulting debug APK is installable for testing and direct sharing. It is not a Google Play production release.
- For a Play Store release, create and securely protect a release signing key, configure signing, build an Android App Bundle (AAB), and complete Play Console requirements.
- The app loads the live KR Store website, so website updates appear in the app without rebuilding it.
