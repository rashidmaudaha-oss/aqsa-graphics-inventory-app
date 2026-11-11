AQSA GRAPHICS INVENTORY SYSTEM — GitHub Actions APK build

This project is an Android WebView wrapper for the existing app:
https://inv.aqsagraphics.com/

It does NOT recreate or modify the Google Sheets database, Apps Script backend,
login system, or inventory data. It loads the existing web app.

Build APK:
1. Upload the contents of this folder to the root of the GitHub repository.
2. Commit the files to the main branch.
3. Open the repository's Actions tab.
4. Select "Build AQSA Inventory APK" and run it if it did not start automatically.
5. Open the completed workflow run and download the artifact named
   AQSA-GRAPHICS-INVENTORY-APK.
6. Extract the downloaded artifact ZIP to get app-debug.apk.

Notes:
- Internet is required.
- Third-party cookies are enabled for the Google Apps Script iframe.
- This is a debug APK for testing, not a Play Store release build.
