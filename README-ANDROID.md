# Farencci — Android Wrapper

This project is a native Android WebView wrapper for the existing Farencci web app.

## Goals
- No browser URL/address bar.
- Load the Farencci web app inside a native Android WebView.
- Preserve the existing web chat/UI.
- Allow camera and microphone permissions for WebRTC audio/video calls.
- Support JavaScript, DOM storage, cookies and media playback.
- Keep links inside the app where possible.

## Configure
1. Open this `android-wrapper` directory in Android Studio.
2. In `app/src/main/java/com/farencci/app/MainActivity.java`, set `APP_URL` to the final Netlify URL if it changes.
3. Build and install the APK.

The wrapper is intentionally separate from the web app so the existing chat code is not modified.
