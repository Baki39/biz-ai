# Biz-AI

Android WebView wrapper for: https://ai.studio/apps/90841f38-ede2-4c7d-9c03-b87773c65312?fullscreenApplet=true

## Quick Start

### Option A — Build APK with GitHub Actions (recommended)
1. Push this folder to a GitHub repository
2. GitHub Actions builds the APK automatically (uses Gradle 8.6)
3. Go to **Actions** tab → latest run → download the APK artifact
4. Sign with your release keystore and upload to Google Play Console

### Option B — Build locally with Android Studio
1. Open this folder in Android Studio
2. Run **Build → Build Bundle(s) / APK(s) → Build APK(s)**
3. Find the APK in `app/build/outputs/apk/debug/`

## App Info
- Package: `com.aistudio.applet`
- Version: 1.0.0 (1)
- Min SDK: API 24 (Android 8)
- Target SDK: API 34
- Orientation: portrait
- Zoom: Enabled
