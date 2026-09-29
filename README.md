# 📱 EvoTask — Official Android Releases

[![Release](https://img.shields.io/github/v/release/ashishjohnd/EvoTask?style=for-the-badge&color=6366f1)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%207.0%2B%20%7C%20Waydroid-34d399?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![APK Size](https://img.shields.io/badge/App%20Size-28.2%20MB-blue?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Offline-First](https://img.shields.io/badge/Storage-100%25%20Offline-9333ea?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)

> **EvoTask** is a polished, lightweight, 100% offline-first productivity and task management Android application built with React Native and Expo. Designed with Material Design principles, fast local search, independent notes, visual analytics, and zero cloud tracking.

---

## 📥 Downloads (v1.0.1)

| Build Variant | Architecture | Size | Recommended For | Direct Download |
| :--- | :--- | :--- | :--- | :--- |
| **📱 Physical Android Phones** | `arm64-v8a` | **28.20 MB** | Modern Android phones (Pixel, Samsung, OnePlus, Xiaomi, etc.) | [**Download APK**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1-arm64.apk) |
| **💻 Universal / Waydroid** | `arm64-v8a` + `x86_64` | **47.05 MB** | Waydroid on Linux, Android Studio emulators, Chromebooks | [**Download APK**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1.apk) |
| **📦 Google Play Store** | Android App Bundle | **24.22 MB** | Google Play Store distribution (AAB) | [**Download AAB**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1.aab) |

> 💡 **Which build should I choose?**
> - If installing on an **Android smartphone or tablet**, download **[`EvoTask-v1.0.1-arm64.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1-arm64.apk)** (68% smaller, just 28 MB!).
> - If running on **Waydroid (Linux)** or an **x86_64 desktop emulator**, download **[`EvoTask-v1.0.1.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1.apk)**.

Check out all release notes and changelogs on the **[Releases Page](https://github.com/ashishjohnd/EvoTask/releases)**.

---

## 🚀 What's New in v1.0.1

- 📉 **Massive APK Size Optimization**: Reduced physical device package size from **88.13 MB down to 28.20 MB (-68.0%)** by eliminating unused font assets and enabling R8/ProGuard dead-code stripping.
- 🎨 **Header Realignment**: Realigned the Home greeting (*"Good afternoon 👋"*) and brand title (*"EvoTask"*) into a cohesive vertical group with a unified 1px gap.
- 📝 **Enhanced Notes UX (View Mode → Edit Mode)**: Tapping notes now opens in a dedicated read-only **View Mode** with zero keyboard disruption. Tapping **[Edit]** allows modifying content, and **[Save]** transitions seamlessly back to View Mode.
- ⚡ **Virtualization & Startup**: Added `React.memo` virtualization to `TaskCard` and `NoteCard` for smooth 60fps scrolling, plus instant 100ms splash fade.

---

## ✨ Features

- **📱 5-Tab Navigation**: Clean, modern interface across `Home`, `Tasks`, `Notes`, `Statistics`, and `Settings` with native safe-area insets.
- **✅ Complete Task Management**: Create, edit, prioritize (`High`, `Medium`, `Low`), categorize (`Work`, `Personal`, `Study`, `Shopping`, `Other`), and set due dates/times with native pickers and overdue detection.
- **📝 Standalone Notes Module**: Completely independent notes system with live full-text search, separate local persistence, and safe read-only viewing.
- **🔒 100% Offline-First Privacy**: Zero account required, zero network dependencies, and zero tracking. All data is persisted locally via `AsyncStorage`.
- **📊 Productivity Analytics**: Visual breakdown of completed, pending, and overdue tasks with category charts.
- **🌓 Adaptive Theming**: Seamless Light, Dark, and System theme switching with a distinctive lavender/purple brand palette.
- **🛡️ Accidental Deletion Protection**: Confirmation dialogs plus animated **UNDO** snackbar for tasks and notes.
- **🤖 Tested on Waydroid & Android**: Fully verified on physical devices, emulators, and Waydroid on Linux.

---

## 📲 How to Install

### On Android Physical Devices
1. Download **[`EvoTask-v1.0.1-arm64.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1-arm64.apk)** (~28 MB).
2. Tap the downloaded file in your notifications or Downloads folder.
3. If prompted, allow **"Install from Unknown Sources"** in your browser/file manager settings.
4. Tap **Install** and open EvoTask!

### On Waydroid (Linux)
1. Download **[`EvoTask-v1.0.1.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1.apk)** (~47 MB).
2. Connect ADB to Waydroid:
   ```bash
   adb connect 192.168.240.112:5555  # or your Waydroid IP
   ```
3. Install the APK:
   ```bash
   adb install -r EvoTask-v1.0.1.apk
   ```
4. Launch EvoTask:
   ```bash
   adb shell am start -n com.evo.evotasks/.MainActivity
   ```

---

## 🏗️ Technical Specifications

- **Framework**: React Native 0.81 (Hermes Bytecode Engine)
- **Toolchain**: Expo SDK 57 (Expo Router v5)
- **Min SDK**: Android 7.0 (API 24)
- **Target SDK**: Android 15 (API 36)
- **Packaging**: Continuous Native Generation (CNG) via EAS Build

---

## 📄 License

Distributed under the [MIT License](https://opensource.org/licenses/MIT).
