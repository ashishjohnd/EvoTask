# 📱 EvoTask — Official Android Releases

[![Release](https://img.shields.io/github/v/release/ashishjohnd/EvoTask?style=for-the-badge&color=6366f1)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Android%207.0%2B%20%7C%20Waydroid-34d399?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![APK Size](https://img.shields.io/badge/App%20Size-47.1%20MB-blue?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)
[![Offline-First](https://img.shields.io/badge/Storage-100%25%20Offline-9333ea?style=for-the-badge)](https://github.com/ashishjohnd/EvoTask/releases/latest)

> **EvoTask** is a fast, lightweight, 100% offline task manager, Pomodoro timer, and notes app for Android. Simple, private, and distraction-free.

---

## 📥 Downloads (v1.0.2)

| Build | Architecture | Size | Download |
| :--- | :--- | :--- | :--- |
| **🚀 Latest Universal APK (v1.0.2)** | `arm64-v8a` + `x86_64` | **47.1 MB** | [**Download EvoTask-v1.0.2.apk**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.2/EvoTask-v1.0.2.apk) |
| **📱 Phone-Only APK (v1.0.1)** | `arm64-v8a` | **28.2 MB** | [**Download EvoTask-v1.0.1-arm64.apk**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1-arm64.apk) |
| **📦 Google Play Bundle (v1.0.1)** | App Bundle (AAB) | **24.2 MB** | [**Download EvoTask-v1.0.1.aab**](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.1/EvoTask-v1.0.1.aab) |

> 💡 **Recommendation**:
> - For all Android phones, tablets, Waydroid (Linux), and PC emulators: download **[`EvoTask-v1.0.2.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.2/EvoTask-v1.0.2.apk)**.

---

## 🌟 Key Features

- **✅ Smart Tasks**: Create, prioritize, categorize, and set due dates with overdue alerts.
- **⏱️ Focus / Pomodoro Mode**: 25m Focus, 5m Short Break, and 15m Long Break intervals with task linkage, timestamp precision, and local history.
- **📱 Customizable Dashboard**: Interactive section reordering (move up/down) and visibility toggles directly from Settings.
- **🔔 Advanced Offline Notifications**: Configurable task due reminders (at due time to 1d before), focus/break completion alerts, and overdue alerts.
- **🎨 Material 3 Accent Themes**: 5 color palettes (Purple, Blue, Green, Orange, Rose) + Compact Mode + Motion controls.
- **📝 Full-Screen Notes**: Full-screen reader & editor with debounced auto-save, 2-column Grid/List view toggle, and Android hardware back button support.
- **📊 Visual Progress**: Progress bar, category breakdowns, and completion trends.
- **🔒 100% Offline & Private**: Zero accounts, zero tracking, zero cloud dependencies. All data stays strictly on your device.
- **🌓 Dark & Light Modes**: Seamless automatic system switching or manual toggle.
- **↩️ Undo Delete**: Instant undo snackbars for tasks and notes.
- **🤖 Multi-Platform**: Fully verified on physical Android phones, emulators, and Waydroid on Linux.

---

## 🚀 What's New in v1.0.2

- **🎯 Built-in Pomodoro Timer**: Isolated timestamp-based timer linking sessions to active tasks without UI lag or drift.
- **🛠️ Dashboard Customization**: Personalize the Home screen layout with movable sections (Greeting, Progress, Quick Add, Focus, Today's Tasks, Overdue, Stats, Notes).
- **🎨 Accent Color Personalization**: Choose between Purple, Blue, Green, Orange, or Rose theme palettes.
- **🗂️ Grid & List View for Notes**: Toggle between 2-column grid cards and full list view with persistent layout memory.
- **📖 Full-Screen Note Experience**: Clean, distraction-free view & edit experience with debounced auto-save.
- **⚙️ Advanced Reminder Offsets**: Customize notification lead time (at due time, 5m, 10m, 15m, 30m, 1h, 1d before).
- **📐 Compact Mode**: Tighter card padding and list gaps for dense information displays.

---

## 📲 How to Install

### On Android Devices
1. Download **[`EvoTask-v1.0.2.apk`](https://github.com/ashishjohnd/EvoTask/releases/download/v1.0.2/EvoTask-v1.0.2.apk)**.
2. Open the downloaded APK from your file manager or browser.
3. Tap **Install** (allow "Install from unknown sources" if prompted).

### On Waydroid (Linux)
```bash
adb connect 192.168.240.112:5555  # or your Waydroid IP
adb install -r EvoTask-v1.0.2.apk
adb shell am start -n com.evo.evotasks/.MainActivity
waydroid show-full-ui
```

---

## 📄 License

Distributed under the [MIT License](https://opensource.org/licenses/MIT).
