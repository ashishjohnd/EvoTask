# 📱 EvoTask — Official Android Releases

[![Release](https://img.shields.io/github/v/release/ashishjohnd/EvoTask?style=for-the-badge&color=6366f1)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%207.0%2B%20%7C%20Waydroid-34d399?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![APK Size](https://img.shields.io/badge/App%20Size-45.6%20MB-blue?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Offline-First](https://img.shields.io/badge/Storage-100%25%20Offline-9333ea?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)

> **EvoTask** is a fast, lightweight, 100% offline task manager, Pomodoro timer, and notes app for Android. Simple, private, and distraction-free.

---

## 📥 Downloads (v1.1.0)

| Build | Architecture | Size | Download |
| :--- | :--- | :--- | :--- |
| **🚀 Latest Universal APK (v1.1.0)** | `arm64-v8a` + `x86_64` | **45.6 MB** | [**Download EvoTask-v1.1.0.apk**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.1.0/EvoTask-v1.1.0.apk) |
| **📱 Universal APK (v1.0.2)** | `arm64-v8a` + `x86_64` | **47.1 MB** | [**Download EvoTask-v1.0.2.apk**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.2/EvoTask-v1.0.2.apk) |
| **📱 Phone-Only APK (v1.0.1)** | `arm64-v8a` | **28.2 MB** | [**Download EvoTask-v1.0.1-arm64.apk**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1-arm64.apk) |
| **📦 Google Play Bundle (v1.0.1)** | App Bundle (AAB) | **24.2 MB** | [**Download EvoTask-v1.0.1.aab**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1.aab) |

> 💡 **Recommendation**:
> - For all Android phones, tablets, Waydroid (Linux), and PC emulators: download **[`EvoTask-v1.1.0.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.1.0/EvoTask-v1.1.0.apk)**.

---

## 🌟 Key Features

- **✅ Smart Tasks**: Create, prioritize, categorize, and set due dates with overdue alerts.
- **⏱️ Focus / Pomodoro Mode**: 25m Focus, 5m Short Break, and 15m Long Break intervals with task linkage, timestamp precision, and local history.
- **🖼️ Proportional Notes Images**: Attached images strictly maintain their natural aspect ratio without distortion, stretching, or being forced into square boxes.
- **🔍 Fullscreen Viewer with Zoom**: Interactive pinch-to-zoom (up to 400%), on-screen zoom stepper (`[-]`, `100%`, `[+]`), two-finger panning, close button, and Android back button integration.
- **📊 Unified Overall Progress Card**: Shared layout across Home and Statistics with single-row header, right-aligned percentage, full-width progress bar, and 3-column metrics.
- **📱 Customizable Dashboard**: Interactive section reordering (move up/down) and visibility toggles directly from Settings.
- **🔔 Advanced Offline Notifications**: Configurable task due reminders (at due time to 1d before), focus/break completion alerts, and overdue alerts.
- **🎨 Material 3 Accent Themes**: 5 color palettes (Purple, Blue, Green, Orange, Rose) + Compact Mode + Motion controls.
- **📝 Full-Screen Notes**: Full-screen reader & editor with debounced auto-save, 2-column Grid/List view toggle, and Android hardware back button support.
- **🔒 100% Offline & Private**: Zero accounts, zero tracking, zero cloud dependencies. All data stays strictly on your device.
- **🌓 Dark & Light Modes**: Seamless automatic system switching or manual toggle.
- **↩️ Undo Delete**: Instant undo snackbars for tasks and notes.
- **⚡ Lightweight & Fast**: Instant launch, smooth 60fps virtualization, and minimal battery consumption.
- **🤖 Multi-Platform**: Standalone Universal 64-bit APK verified on physical Android phones, emulators, and Waydroid on Linux.

---

## 🚀 What's New in v1.1.0

- **🖼️ Proportional Notes Image Display**: Natural aspect ratio preservation, scale presets (Small 72%, Medium 88%, Large 100%, Custom 50%–100%), lossless `quality: 1.0` gallery picker, individual 3-dot context menu, and interactive fullscreen viewer with pinch zoom (up to 4x) & pan.
- **📊 Unified Overall Progress Card**: Single reusable `OverallProgressCard` across Home and Statistics with standard 16dp outer screen margin, 16dp internal padding, single-row header, right-aligned percentage, full-width progress bar, and 3-column statistics metrics with aligned baselines.
- **📐 Compact Dashboard Rhythm**: Refined vertical card rhythm and section padding without reducing touch targets (44–48dp minimum).
- **🎨 Visual Identity & Polish**: Updated Material 3 adaptive icon, monochrome icon, and author credit set to Ashish John.
- **📦 Standalone Universal 64-Bit APK**: Single Universal APK (`EvoTask-v1.1.0.apk`) containing both `arm64-v8a` (physical devices) and `x86_64` (Waydroid / PC emulators), pre-compiled with Hermes bytecode.

---

## 📲 How to Install

### On Android Devices
1. Download **[`EvoTask-v1.1.0.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.1.0/EvoTask-v1.1.0.apk)**.
2. Open the downloaded APK from your file manager or browser.
3. Tap **Install** (allow "Install from unknown sources" if prompted).

### On Waydroid (Linux)
```bash
adb connect 192.168.240.112:5555  # or your Waydroid IP
adb install -r EvoTask-v1.1.0.apk
adb shell am start -n com.evo.evotasks/.MainActivity
waydroid show-full-ui
```

---

## 📄 License

Distributed under the [MIT License](https://opensource.org/licenses/MIT).
