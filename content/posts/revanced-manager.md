---
title: revanced-manager
date: 2023-08-29T12:16:59+08:00
draft: False
featuredImage: https://images.unsplash.com/photo-1690834787964-3fbac1bcd362?ixid=M3w0NjAwMjJ8MHwxfHJhbmRvbXx8fHx8fHx8fDE2OTMyODI0NjV8&ixlib=rb-4.0.3
featuredImagePreview: https://images.unsplash.com/photo-1690834787964-3fbac1bcd362?ixid=M3w0NjAwMjJ8MHwxfHJhbmRvbXx8fHx8fHx8fDE2OTMyODI0NjV8&ixlib=rb-4.0.3
---

# [ReVanced/revanced-manager](https://github.com/ReVanced/revanced-manager)

# 💊 ReVanced Manager

The official ReVanced Manager based on Flutter.

## 🔽 Download
To download latest Manager, go [here](https://github.com/revanced/revanced-manager/releases/latest) and install the provided APK file.

## 📝 Prerequisites
1. Android 8 or higher
2. Does not work on some armv7 devices

## 🔴 Issues
For suggestions and bug reports, open an issue [here](https://github.com/revanced/revanced-manager/issues/new/choose).

## 💭 Discussion
If you wish to discuss the Manager, a thread has been made under the [#development](https://discord.com/channels/952946952348270622/1002922226443632761) channel in the Discord server, please note that this thread may be temporary and may be removed in the future.


## 🌐 Translation
[![Crowdin](https://badges.crowdin.net/revanced/localized.svg)](https://crowdin.com/project/revanced)

If you wish to translate ReVanced Manager, we're accepting translations on [Crowdin](https://translate.revanced.app)

## 🛠️ Building Manager from source
1. Setup flutter environment for your [platform](https://docs.flutter.dev/get-started/install)
2. Clone the repository locally
3. Add your github token in gradle.properties like [this](/docs/4_building.md)
4. Open the project in terminal
5. Run `flutter pub get` in terminal
6. Then `flutter packages pub run build_runner build --delete-conflicting-outputs` (Must be done on each git pull)
7. To build release apk run `flutter build apk`
