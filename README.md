# DESTINY FINCO for Android

**Download page:** https://theanushree25.github.io/destiny-finco-app/

This repository only hosts the Android app's download page and APK releases. It contains no source code.

- Latest APK: [DestinyFinco.apk](https://github.com/TheAnushree25/destiny-finco-app/releases/latest/download/DestinyFinco.apk). Each release also carries a uniquely named copy, `DestinyFinco-<versionName>-build<versionCode>.apk`.
- `latest.json` tells installed apps when a newer **native** build is available. Raise `versionCode` with each release, and point `apkUrl` at the uniquely named APK with its `sizeBytes` and `md5`.
- JS-only changes don't need a release here. From build 3 (0.1.0) on, they ship over the air with EAS Update (`npm run ota` in the app repo; see its `docs/RELEASING.md`).
