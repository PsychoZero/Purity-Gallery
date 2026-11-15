# Purity Gallery

A private, local-only media gallery for Android. No cloud, no internet access, no accounts, no data leaving your device.

Purity Gallery points at a folder of photos, videos and comics and gives you a fast, tag-driven.

> **Status:** Early development. Android first. Windows and Linux versions are planned after the Android version is finished.

---

## Privacy

- Works entirely on your device
- No analytics, no telemetry, no ads
- No cloud features and no external data sharing
- Your library stays in plain folders you control

## Features

**Browsing**
- Dense, uniform thumbnail grid with lazy-loaded thumbnails
- Grid adapts to screen width and orientation
- Configurable items per page (e.g. 50 / 100 / 200); your choices are remembered
- Fit-to-tile by default, with a fill/crop option
- Optional overlays: filename, date, video duration, favorite, plus a play icon on videos

**Search and tags**
--style search bar with combined tags, `-tag` exclusion and `sort:` expressions
- Post page showing the media with its tags and details; tap a tag to search it
- Tags, notes and links on every file
- Folders inside your main folder act as tickable filters

**Media support**
- Images, videos, GIFs, SVGs and RAW photos (via embedded JPEG preview)
- Inline video playback
- Built so more formats can be added later

**Comics**
- Group pages into a named comic, strip or chapter with explicit page numbers
- Contact-sheet view
- Reader with single-page, two-page spread and continuous vertical scroll modes
- Left-to-right or right-to-left reading order
- Tags and notes at both page and comic level
- A grouped comic appears as one expandable cover tile

**Library management**
- In-app import for adding photos and videos
- Removable storage (SD card) detection
- Option to show hidden files
- Recycle bin and a clean-up screen in settings
- PIN, pattern or fingerprint app lock

## How your data is stored

Your media stays in your main folder, untouched. Tags, notes and links are stored in a separate metadata folder next to it, not inside it. This means you can back up or sync the metadata on its own, and the app reconciles it automatically if files change. Backup and restore covers the metadata files.

Purity Gallery does not handle syncing itself. If you want your library on several devices, use a tool like Syncthing to keep the folders in step.

## Download and install

Purity Gallery is **not on the Play Store** and is distributed as a signed APK through this repository's **Releases** page.

1. Open the [Releases](../../releases) page and download the latest `.apk`.
2. On your phone, allow installs from this source when prompted (Settings → Apps → Special access → Install unknown apps, then pick your browser or file manager).
3. Open the downloaded file and tap **Install**.
4. Google Play Protect may warn about an app it doesn't recognise. Choose **Install anyway** if you trust the source.
5. On first launch, pick your main media folder and grant storage access.

**Requirements:** Android phone or tablet. Minimum Android version: _TBD_.

## What it won't do

Purity Gallery is a viewer and organiser. It deliberately does not include photo or video editing, or any sharing features.

## Roadmap

- [ ] Finish and stabilise the Android version
- [ ] Windows version (reads the same metadata files)
- [ ] Linux version (reads the same metadata files)

## License

Proprietary. All rights reserved.

This repository contains release binaries only. The source code is not published. You may download and use the app for personal use, but you may not redistribute, modify, decompile or resell it without written permission.

## Bugs and what not

Report bugs on github. If a feature desired, just leave a comment.

