# Expense Calculator – Android APK project

App name: **Expense Calculator**  (package: com.tarun.expensecalculator) – wallet icon in assets/

## Option A – No installs (GitHub, free)
1. Create a new GitHub repository and upload everything in this folder (including the hidden .github folder).
2. Open the repo > Actions tab > "Build APK" > wait ~5 min.
3. Download the artifact "ExpenseCalculator-APK" (zip) > unzip > app-debug.apk.
4. Copy to your phone, tap to install (allow "Install unknown apps").

## Option B – On your PC (needs Node 18+, JDK 17, Android SDK)
    npm install
    npm run build:apk
APK: android/app/build/outputs/apk/debug/app-debug.apk

The Excel/PDF libraries are fetched from npm automatically.
Exports open the Android share sheet (Save to Drive / Files / WhatsApp).
