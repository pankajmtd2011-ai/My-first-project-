# Gaming Style Panel (Android project)

A standalone Android Studio project for a black/red gaming-style panel.

## Android-only build using GitHub Actions
1. Extract this ZIP on your phone.
2. In a browser, sign in to GitHub and create a new repository.
3. Upload the project files and folders to the repository's `main` branch. Make sure `.github/workflows/build-apk.yml` is included.
4. Open the repository's **Actions** tab. If prompted, enable Actions.
5. Open **Build Android APK** and tap **Run workflow** (or wait for the first push build).
6. When the run finishes successfully, open the run and download the artifact named `GamingStylePanel-debug-apk`.
7. Extract the artifact ZIP on your phone. It contains `app-debug.apk`.
8. Tap the APK to install. Android may ask you to allow installs from that browser/file manager; only allow it for the source you trust.

## Local computer build
Open the project in Android Studio, sync Gradle, then choose Build > Build APK(s).

## Included
- Main, Visual, Movement, and Misc tabs
- Interactive demo toggles and sliders
- Portrait mobile layout
- No network permissions and no integration with Free Fire or other games

This is source code, not a prebuilt APK. The controls modify only the standalone demo UI.
