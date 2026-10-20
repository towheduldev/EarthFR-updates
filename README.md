# EarthFR Android downloads

This public repository distributes signed EarthFR Android APKs and update information only. Game source and signing/publishing keys are kept in the private development repository.

Download **EarthFR.apk** from a [versioned release](https://github.com/towheduldev/EarthFR-updates/releases). Install it over the existing game to preserve saves. The Android app can check for future updates at launch/resume, offer a download, ask Android to install it, and remove its private temporary download afterward. The first updater-enabled version requires a manual installation.

[Update feed](https://raw.githubusercontent.com/towheduldev/EarthFR-updates/main/latest.json). Releases attach **only the APK**. Checksum/version information is served separately for the updater. GitHub's automatic source archive links contain distribution files, not the private game source. Android version codes distinguish successive pushes even when the displayed game version is unchanged. Keep the same APK signing identity. Android asks for installation approval and, initially, permission for EarthFR to install updates. No dedicated update server or player GitHub login is required.
