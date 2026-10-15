# Relay — Downloads

**Relay** lets you monitor and control your Antigravity AI coding sessions from your phone. It pairs a local desktop agent with a mobile app through a secure broker, so your code, terminal, and workspace stay on your own computer.

This repository hosts the **public download builds**. Source code is kept in a separate private repository.

> Website: **https://relayx.dev**

---

## ⬇️ Download the latest build

Latest release: **v8.4.49** — get every platform from the [**Releases page →**](https://github.com/cudanexus/relayx/releases/latest)

| Platform | Download | Notes |
|----------|----------|-------|
| **macOS — Apple Silicon (M-series)** | [Relay-macOS-ARM.dmg](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-ARM.dmg) · [.zip](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-ARM.zip) | ✅ Signed & notarized by Apple |
| **macOS — Intel** | [Relay-macOS-Intel.dmg](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-Intel.dmg) · [.zip](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-Intel.zip) | ✅ Signed & notarized by Apple |
| **Windows (x64)** | [Relay-Windows.exe](https://github.com/cudanexus/relayx/releases/latest/download/Relay-Windows.exe) | Unsigned — SmartScreen warns on first run |
| **Linux (x64)** | [Relay-Linux.AppImage](https://github.com/cudanexus/relayx/releases/latest/download/Relay-Linux.AppImage) · [.deb](https://github.com/cudanexus/relayx/releases/latest/download/Relay-Linux.deb) | Ubuntu 20.04 or newer |
| **Android** | [Relay-Android.apk](https://github.com/cudanexus/relayx/releases/latest/download/Relay-Android.apk) | Enable "Install unknown apps" to sideload |
| **iOS** | **TestFlight** (build 23) | Public download not available — request a TestFlight invite |

---

## ✨ Latest changes (v8.4.49)

- **Relay now updates itself.** The desktop app checks for new versions in the background, downloads them quietly, and installs them the next time Relay restarts. Choose **Restart to Update** from the app menu, the notification, or your phone (Settings › About) to install right away. Relay never restarts on its own while you work.
- **More reliable connection** — if the relay service is updated, your computer reconnects on its own instead of showing "Desktop offline" until Relay is restarted.
- **Security hardening** — pairing details and session controls are only available on the computer itself, never through the relay or a local tunnel.
- Rebuilt every desktop platform: macOS (Apple silicon + Intel, signed and notarized), Windows, Linux (AppImage + .deb), Android.

> On v8.4.48 or older? Download v8.4.49 once — every version after that arrives by itself.

---

## 🚀 Getting started

1. **Download** the build for your platform above.
2. **Install & launch** the desktop app on the computer running Antigravity.
3. **Pair your phone** with a six-digit PIN, QR code, app link, local Wi-Fi, or broker session URL.
4. Monitor the active chat, send prompts, and run stop / new-chat actions — all from your phone.

Your Antigravity session, terminal, and files never leave your computer; the phone is a remote control.

---

## 🛡️ Install notes

**macOS:** the apps are **signed and notarized by Apple**, so they open normally — just drag Relay to Applications and launch it.

**Windows (unsigned):** SmartScreen shows a warning on first run — click **More info → Run anyway**.

**Android:** allow installing from unknown sources for your browser/file manager, then open the APK.

---

## ❓ Support

- Website: https://relayx.dev
- Issues with a build: open an issue on this repository.
