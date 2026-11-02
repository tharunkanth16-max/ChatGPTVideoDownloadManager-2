# Chatgptvideodownloadermanager2

Starter Android app for downloading direct HTTP/HTTPS video-file URLs with Android DownloadManager.

## GitHub Actions build
1. Extract this ZIP.
2. Upload the **contents** of this folder to the root of your GitHub repository; do not upload only the ZIP.
3. Keep `.github/workflows/build-apk.yml` at that exact path.
4. Commit the files to `main`.
5. Open **Actions** and run **Build Android APK**.
6. Download the `Chatgptvideodownloadermanager2-debug-apk` artifact from a successful run.

## Project
- App label: Chatgptvideodownloadermanager2
- Application ID: `com.chatgptvideodownloadermanager2`
- Minimum Android: 10 (API 29)
- Compile/target SDK: 35
- Java: 17; Android Gradle Plugin: 8.7.3; Gradle: 8.9

## Limitations
Direct video-file URLs only. It does not extract videos from YouTube/social-media pages or bypass DRM, sign-in, paywalls, or website restrictions. Only download content you own or have permission to save.
