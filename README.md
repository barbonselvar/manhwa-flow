# Manhwa Flow

Native Android engineering test build for Android 13 and newer. This repository is the distribution location for the existing prebuilt APK; publishing does not rebuild or change the application.

Download the Android test prerelease from [Releases](https://github.com/barbonselvar/manhwa-flow/releases). Choose `ManhwaFlow-debug.apk`. Its SHA-256 checksum is published alongside it.

App: `com.manhwaflow`, version 0.1.0, minimum API 33, target API 35. The APK uses Android development signing and includes ARM64 libraries.

This is an engineering test build. Real OCR, on-device Arabic translation, caching, and Arabic text rendering passed component tests. Full native continuous-reading/capture acceptance is incomplete; no physical phone, including the Galaxy S24, was tested. Universal overlays are partly translucent to preserve Android touch-through behavior.

No signing keys, API secrets, or private configuration are published here.
