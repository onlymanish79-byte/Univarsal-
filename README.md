# UNIVERSAL MUSIC — Android starter project

A dark, Apple-Music-inspired Android music player starter built with Kotlin, Jetpack Compose and AndroidX Media3.

## Current working features
- Dark premium-style home, search and library tabs
- Reads music files available on the device after permission is granted
- Plays local audio with Media3 ExoPlayer
- Mini-player with play/pause
- Android 8.0+ minimum target

## Important limitations
This is a functional local-library MVP, not yet a global licensed streaming service. It does not include a music catalogue API, accounts/cloud sync, playlists persistence, downloads, background MediaSession service, or an APK binary. Those require additional backend, provider licensing, and implementation.

Do not scrape or download copyrighted music. Add streaming/download providers only when their terms and track licences explicitly allow it.

## Build an APK
1. Install Android Studio (latest stable) and JDK 17.
2. Open this folder in Android Studio.
3. Let Gradle sync complete.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. The debug APK will be under `app/build/outputs/apk/debug/`.

## App identity
Package: `com.universalmusic.app`
Version: `1.0.0`
Minimum Android: 8.0 (API 26)
