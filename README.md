# 📱 EvoTask — Official Android Releases

[![Release](https://img.shields.io/github/v/release/ashishjohnd/EvoTask?style=for-the-badge&color=6366f1)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Waydroid-34d399?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)

> **EvoTask** is a polished, lightweight, 100% offline-first productivity and task management Android application built with React Native and Expo.

---

## 📥 Download Latest APK

👉 **[Download EvoTask-v1.0.0.apk](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.0/EvoTask-v1.0.0.apk)** *(~88 MB)*

You can also view all release notes and changelogs on the **[Releases Page](https://github.com/ashishjohnd/EvoTask/releases)**.

---

## ✨ Features

- **5-Tab Navigation**: Clean, modern interface with Home, Tasks, Notes, Statistics, and Settings tabs, designed with native safe-area insets.
- **Task Management**: Create, edit, prioritize (High/Medium/Low), categorize (Work, Personal, Study, Health, Other), and set due dates/times with native pickers and overdue detection.
- **Standalone Notes**: Independent rich notes system with live full-text search, separate local persistence, and multiline editing.
- **100% Offline-First**: Instant startup with zero cloud latency. All data is securely stored locally on your device via AsyncStorage.
- **Productivity Statistics**: Visual breakdown of completed, pending, and overdue tasks with category charts.
- **Tested on Waydroid & Android**: Fully verified on Android physical devices, emulators, and Waydroid on Linux.

---

## 📲 How to Install

### On Android Devices
1. Download the `.apk` file using the link above.
2. Tap the downloaded file in your notifications or Downloads folder.
3. If prompted, allow "Install from Unknown Sources" in your browser/file manager settings.
4. Tap **Install** and open EvoTask!

### On Waydroid (Linux)
```bash
adb connect 192.168.240.112:5555  # or your Waydroid IP
adb install -r EvoTask-v1.0.0.apk
```
