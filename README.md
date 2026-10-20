# Haier TV Home

An adapted Android TV launcher trial for a low-memory Haier Android 11 television, based on [Gathin23/tv-vibehack](https://github.com/Gathin23/tv-vibehack), upstream snapshot `31eb392042009d41bc4ab4b9afadc253db7ab6d6`.

## Contents

Android launcher source, Gradle wrapper, build configuration, fonts, and build/install helper scripts. Original device logs, device identifiers, trial APKs, and raw optimization evidence are excluded.

## Build

Use a compatible JDK and Android SDK, set `ANDROID_HOME` or local SDK properties, and run `./gradlew assembleDebug`. Inspect installation scripts before running them; they interact with a connected device. Building alone does not require installing or changing the default home app.

## Status

Built, installed, and trialled on the original device. On-screen navigation and app/Settings/input activity launches were demonstrated. Physical remote behavior, HDMI picture/audio, playback/DRM, Cast, default-HOME behavior, and reboot recovery remain incompletely verified. No measured performance improvement is claimed.

## Attribution

Upstream launcher: Gathin, MIT license, retained in `LICENSE`. Outfit font: SIL Open Font License, retained in `FONT-LICENSE-OFL.txt`. Adaptation and device-specific trials by Aslam. Preserve these notices when redistributing.
