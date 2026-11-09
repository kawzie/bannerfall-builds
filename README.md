# Bannerfall — Android builds

Download and play the latest Bannerfall development build.

## Download

**[Download Bannerfall.apk](https://github.com/kawzie/bannerfall-builds/releases/download/v0.1.0-alpha.4/Bannerfall.apk)**

[Release notes and checksums](https://github.com/kawzie/bannerfall-builds/releases/tag/v0.1.0-alpha.4) · [All builds](https://github.com/kawzie/bannerfall-builds/releases)

The APK download is approximately **1.1 GB**. This is an early Android development
build for testing. This repository distributes builds and release notes.

## Install on Android

1. Open the download link on your Android device.
2. Download `Bannerfall.apk`, then open the downloaded file.
3. If Android asks, allow your browser or file manager to install apps, then
   confirm installation.
4. Open **Bannerfall**.

## Play

- **Battle → Find Match** connects to public matchmaking on the hosted server.
- Both players must have this updated build and choose **Find Match**. The first
  player waits until another player joins the queue.
- **Battle → Practice vs AI** starts an offline match against the computer.
- Opening the menu during an online match does not pause it. Leaving an active
  online match forfeits it to the opponent.

Online multiplayer requires an internet connection and the development server
to be available. This build includes banner customization, the medieval menu
and battlefield artwork, and server-controlled multiplayer matches.

## Battlefield artwork

The latest build restores a restrained low-poly look to the grass, with broad
subtle facets and gently angular worn patches. The field stays flat and open,
with the same path, walls, gates, shop, and animated scenery.

## Aura coverage

- Level 1: four side-adjacent tiles, without diagonals.
- Level 2: adds the four inner diagonal neighbors (eight affected tiles).
- Level 3: keeps those eight and adds the next tile straight out in each direction
  (twelve affected tiles). Outer diagonals are excluded.

The blue dashed outline follows the actual coverage at each level.
Online play requires 0.1.0-alpha.3 or newer on both devices.

## Build information

| Item | Value |
|---|---|
| Release | `v0.1.0-alpha.4` |
| Build date | November 8, 2026 (Pacific time) |
| Platform | Android ARM64 |
| Download | `Bannerfall.apk` |
| Integrity file | `SHA256SUMS.txt` in the release assets |

The Releases page contains the installable APK. GitHub's automatic source ZIP
and tar downloads contain this repository's documentation rather than the game.
