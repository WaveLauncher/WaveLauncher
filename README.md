<div align="center">

<img src="README/title.png" alt="Wave Launcher" width="460">

# Wave Launcher

**A controller-first Android launcher inspired by the PlayStation 3 XrossMediaBar.**

<a href="https://github.com/WaveLauncher/WaveLauncher/releases">
  <img src="https://img.shields.io/badge/download-releases-085e5e?style=for-the-badge&labelColor=black" alt="Downloads">
</a>
<a href="https://discord.gg/g9mJ9vwx">
  <img src="https://img.shields.io/discord/1494750423297560606?label=discord&logo=discord&logoColor=white&style=for-the-badge&color=5865F2&labelColor=black" alt="Discord">
</a>
<a href="https://www.patreon.com/cw/WaveLauncher">
  <img src="https://img.shields.io/badge/support%20us-patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white&labelColor=black" alt="Patreon">
</a>
<a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://add/https%3A%2F%2Fgithub.com%2FWaveLauncher%2FWaveLauncher">
  <img src="https://img.shields.io/badge/obtainium-add-6238b4?style=for-the-badge&logo=obtainium&logoColor=white&labelColor=black" alt="Add to Obtainium">
</a>

</div>

---

## About

Wave Launcher is an Android-based interface built around the design of the XrossMediaBar (XMB/PS3). It supports personal game libraries, rich metadata scraping, trophy tracking and controller-friendly multimedia playback.

> [!NOTE]
> Wave Launcher is a **frontend**, not an emulator. Install and configure the emulators you want to use separately.

## Showcase

<table>
  <tr>
    <td align="center" width="50%">
      <img src="README/home.png" alt="Wave Launcher home screen" width="100%">
      <br><strong>Home & Libraries</strong>
      <br><sub>Start with a clean library, then make Wave Launcher your own with collections, favorites, playtime, and personalized layouts.</sub>
    </td>
    <td align="center" width="50%">
      <img src="README/scraper.png" alt="Metadata scraper" width="100%">
      <br><strong>Metadata Scraping</strong>
      <br><sub>Give every game more character with artwork, descriptions, covers, sounds, and details from multiple sources.</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="README/retroachievements.png" alt="RetroAchievements integration" width="100%">
      <br><strong>Achievements</strong>
      <br><sub>Keep your progress close at hand and turn every session into another step toward your next achievement.</sub>
    </td>
    <td align="center">
      <img src="README/change_color.png" alt="Wallpaper color customization" width="100%">
      <br><strong>Customization</strong>
      <br><sub>Shape the look and feel of your launcher with custom wallpapers, colors, fonts, sounds, and interface scale.</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="README/settings.png" alt="Wave Launcher settings" width="100%">
      <br><strong>Settings</strong>
      <br><sub>Fine-tune your setup, connect your libraries, choose your integrations, and keep control of how Wave Launcher behaves.</sub>
    </td>
    <td align="center">
      <img src="README/software_update.png" alt="Software Updater" width="100%">
      <br><strong>Software Updater</strong>
      <br><sub>Keep Wave Launcher current, import supported software sources, and set up standard or dual-screen emulation packs from one place.</sub>
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <img src="README/video-player.png" alt="Video player" width="50%">
      <br><strong>Media</strong>
      <br><sub>Enjoy your videos, music, and photos with controller-friendly playback that fits naturally into your launcher.</sub>
    </td>
  </tr>
</table>

## Install & Updates

Download the latest APK from the [Releases page](https://github.com/WaveLauncher/WaveLauncher/releases/latest) and install it on your Android device. For future updates, open **Settings 🠊 Software Update** in the app. The updater can check for and install new Wave Launcher releases, while also helping you import supported software sources and install or update emulators via your own Obtainium JSON or the RJNY Emulation Pack.

## Features

### Controller & Navigation

- XMB-style navigation designed around gamepads and touch.
- Support for PlayStation, Xbox, Nintendo, and virtual controllers.
- Controller-specific prompts, customizable button layouts, AB / XY swapping, and a gamepad-friendly on-screen keyboard.
- On-Screen Controller for devices that do not have a physical controller.

### Game Libraries

- Organize platforms, collections, favorites, recently played games, and playtime.
- Storage labels, icons, hot-swap support, and external-storage autorun.inf support.
- Per-platform and per-game emulator assignments.

### Scraping & Achievements

- Game Metadata scraping through services including [SteamGridDB](https://www.steamgriddb.com/), [ScreenScraper](https://www.screenscraper.fr/), [RetroAchievements](https://retroachievements.org/), [Hasheous](https://hasheous.org/), Google Play, and Web Search.
- Multi-language scraper support.
- RetroAchievements and Dusklight (TwilitRealm) achievement tracking.

### Media & Customization

- Controller-friendly video, music, and photo playback.
- Background music, coldboot sounds, and separate volume controls.
- Wallpaper styles, color customization, brightness controls, and custom fonts.
- Interface scaling, text sizing, status bar options, boot logos, and custom UI sounds.

### Device Integration

- Dual-screen layouts with per-screen orientation, app placement, screen swapping, and docked mode.
- Android app discovery with clear separation between games, emulators, and apps.
- Encrypted FTPS file sharing for moving files to and from a device.
- HTTPS Wave Portal for managing supported launcher content from a browser (experimental).
- Quick first-run setup, custom paths, and existing-file detection.


### Metadata Sources

[SteamGridDB](https://www.steamgriddb.com/) · [ScreenScraper](https://www.screenscraper.fr/) · [RetroAchievements](https://retroachievements.org/) · [Hasheous](https://hasheous.org/) · [Google Play](https://play.google.com/)

### Open Source Foundations

[FFmpeg](https://ffmpeg.org/) · [AndroidX](https://developer.android.com/jetpack/androidx) · [LGPL-2.1](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html) · [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
