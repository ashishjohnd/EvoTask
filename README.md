# 📱 EvoTask — Official Android Releases

[![Release](https://img.shields.io/github/v/release/ashishjohnd/EvoTask?style=for-the-badge&color=6366f1)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%207.0%2B%20%7C%20Waydroid-34d399?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![APK Size](https://img.shields.io/badge/App%20Size-48.3%20MB-blue?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Offline-First](https://img.shields.io/badge/Storage-100%25%20Offline-9333ea?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)

> **EvoTask** is an offline-first Android productivity application built with React Native and Expo, featuring smart task management, markdown notes with image attachments, Pomodoro focus tracking, and Material 3 design.

---

## 📥 Download Latest Release (v1.1.0)

| Build | Architecture | Size | Download |
| :--- | :--- | :--- | :--- |
| **🚀 Universal APK (v1.1.0)** | `arm64-v8a` + `x86_64` | **48.3 MB** | [**Download EvoTask-v1.1.0.apk**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.1.0/EvoTask-v1.1.0.apk) |

> 💡 **Universal Compatibility**:
> Compatible with both physical Android devices (`arm64-v8a`) and Linux Waydroid / PC emulators (`x86_64`).

---

## 🌟 Key Features

- **Task Management**: Prioritize, categorize, set due dates, and track active vs. completed tasks with overdue notifications.
- **Focus Timer**: Integrated Pomodoro timer with Focus, Short Break, and Long Break intervals, task linking, and session history.
- **Full-Screen Notes**: Distraction-free editor with debounced auto-save, grid/list view toggles, and image attachments.
- **Proportional Image Viewer**: Preserves native image aspect ratios with customizable display scaling and interactive pinch-to-zoom.
- **Progress Overview**: Unified progress card across Home and Statistics showing completion rates, active workloads, and weekly trends.
- **Customizable Dashboard**: Reorder sections and toggle card visibility directly from Settings.
- **Offline Notifications**: Configurable local alerts for task due dates, overdue items, and completed focus intervals.
- **Material 3 Themes**: Light and dark modes with 5 accent color palettes and compact density settings.
- **100% Offline & Private**: Zero accounts, zero analytics, and zero cloud dependencies—all data stays on your device.
- **Fast & Responsive**: Optimized Hermes bytecode execution delivering smooth 60fps performance and minimal battery usage.

---

## 🚀 What's New in v1.1.0

- **Proportional Note Images**: Attached images retain their native aspect ratio without distortion or cropping. Sizing can be adjusted via Small (~72%), Medium (~88%), Large (100%), and Custom scale presets.
- **Full-Screen Image Viewer**: Added interactive pinch-to-zoom (up to 4x), two-finger panning, and dedicated on-screen zoom controls.
- **Unified Progress Card**: Standardized progress layout across Home and Statistics screens for consistent metrics and alignment.
- **Refined Dashboard Spacing**: Streamlined card heights and vertical gaps for higher information density while preserving accessible touch targets.
- **Universal 64-Bit Binary**: Standalone APK supporting both `arm64-v8a` (phones/tablets) and `x86_64` (Waydroid and emulators).
- **Visual Identity & Polish**: Refreshed Material 3 adaptive app icons and refined interface details.

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
