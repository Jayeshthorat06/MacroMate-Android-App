MACROMATE - PRIVATE ANDROID PROJECT
===================================

This is an Android Studio project for a private, offline-first nutrition tracker.
It wraps the included HTML interface inside a native Android WebView, so the user
launches it from an app icon and does not need Chrome.

FEATURES
- Daily calorie, protein, carb and fat totals
- Quick-add food list with common Indian foods
- Custom foods
- Food log by meal
- Weight history
- Editable nutrition targets
- JSON backup and restore
- Data stored locally on the device; no account and no network permission

BUILD AN APK
1. On a computer, install Android Studio (official: https://developer.android.com/studio).
2. Extract this ZIP.
3. In Android Studio choose Open and select the extracted MacroMateAndroid folder.
4. Let Gradle sync and install the Android SDK platform requested by the project if prompted.
5. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Android Studio will show a notification with a link to the generated APK (typically app/build/outputs/apk/debug/app-debug.apk).
7. Transfer that APK to your Android phone and open it. If Android asks, allow installation from that file source.

NOTES
- This ZIP is source code, not a precompiled APK.
- No online account or web hosting is needed to use the app after installation.
- App data is local to this app installation. Export a JSON backup before uninstalling or changing phones.
- Nutrition values are estimates; use food labels and measured portions where possible.
