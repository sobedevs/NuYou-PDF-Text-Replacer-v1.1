NuYou PDF Text Replacer — Pre-signed Build

This project auto-generates a generic keystore on first build and produces a SIGNED release APK.

Steps:
1) Open in Android Studio.
2) Build → Build APK(s).
3) Output: app/build/outputs/apk/release/app-release.apk (already signed).

Keystore:
- Path: app/keystore/nuyouplus-generic.jks
- Alias: nuyou
- Passwords: nuyou2025
(Generated locally by Gradle `preBuild` on first run; no file shipped here for security.)
