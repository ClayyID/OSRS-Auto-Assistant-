# OSRS Auto Assistant (Android)

A Kotlin + Jetpack Compose standalone companion app with a dark OSRS-inspired interface.

## Included
- Home dashboard
- XP tracker (session-only demo state)
- OSRS XP calculator (level 1–99 curve)
- Session timer and interval reminder counter
- List of all 23 OSRS skills
- Settings screen

## Important automation boundary
The interval tool is a timer/reminder only. This project does not inject taps, automate gameplay, read the OSRS screen, or bypass Jagex protections. It is designed as a companion utility.

## Build APK
1. Install Android Studio (current stable) and Android SDK Platform 35.
2. Open this project folder in Android Studio.
3. Allow Gradle sync to complete.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Find the debug APK under `app/build/outputs/apk/debug/app-debug.apk`.

## Requirements
- Android Studio with JDK 17
- Android SDK 35
- Minimum Android 8.0 (API 26)

This is a starter implementation. XP tracker data is currently held in memory; persistent storage and official hiscores integration can be added in a later version.
