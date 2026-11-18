# AeroSense – Android app

A WebView wrapper around Aerosense.html (stored in app/src/main/assets/index.html).
Cleartext HTTP is enabled so the app can talk to your ESP32 on the local network.

## Option A – GitHub Actions (no installs, works from a phone/browser)
1. Create a free GitHub repo and upload everything in this folder
   (including the hidden .github folder).
2. Open the Actions tab > "Build APK" > wait ~3 minutes.
3. Download the "AeroSense-apk" artifact (zip), unzip, open the .apk on your phone.

## Option B – Android Studio
1. File > Open, select this folder, let Gradle sync.
2. Build > Build APK(s). Output: app/build/outputs/apk/.

## Installing
Open the .apk on your phone and allow "Install unknown apps" when asked.

## Updating the UI later
Replace app/src/main/assets/index.html with the new file and rebuild.
