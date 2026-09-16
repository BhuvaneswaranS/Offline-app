# Phone-only build

This version is prepared for a phone-only workflow.

## Recommended route: GitHub Actions
1. Create a GitHub account using your phone.
2. Create a new repository named `OfflineAIEditor`.
3. Upload the contents of this folder to the repository (GitHub mobile/web works from a phone).
4. Open the repository's **Actions** tab.
5. Run **Build Offline AI Editor APK**.
6. Open the completed workflow run and download the `OfflineAIEditor-debug-apk` artifact.
7. Extract the APK and install it on your Android phone.

The project itself does not request INTERNET permission. Once installed, Version 1 performs image editing locally.

## Important
This is a debug APK for testing, not a Play Store release. Android may require you to allow installation from the browser/file manager you use to open the APK.
