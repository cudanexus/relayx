# Relay — Downloads

**Relay** lets you monitor and control your Antigravity AI coding sessions from your phone. It pairs a local desktop agent with a mobile app through a secure broker, so your code, terminal, and workspace stay on your own computer.

This repository hosts the **public download builds**. Source code is kept in a separate private repository.

> Website: **https://relayx.dev**

---

## ⬇️ Download the latest build

Latest release: **v8.1.3** — get every platform from the [**Releases page →**](https://github.com/cudanexus/relayx/releases/latest)

| Platform | Download | Notes |
|----------|----------|-------|
| **macOS — Apple Silicon (M-series)** | [Relay-macOS-ARM.dmg](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-ARM.dmg) · [.zip](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-ARM.zip) | ✅ Signed & notarized by Apple |
| **macOS — Intel** | [Relay-macOS-Intel.dmg](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-Intel.dmg) · [.zip](https://github.com/cudanexus/relayx/releases/latest/download/Relay-macOS-Intel.zip) | ✅ Signed & notarized by Apple |
| **Windows (x64)** | [Relay-Windows.exe](https://github.com/cudanexus/relayx/releases/latest/download/Relay-Windows.exe) | Unsigned — SmartScreen warns on first run |
| **Android** | [Relay-Android.apk](https://github.com/cudanexus/relayx/releases/latest/download/Relay-Android.apk) | Enable "Install unknown apps" to sideload |
| **iOS** | **TestFlight** (build 23) | Public download not available — request a TestFlight invite |

---

## ✨ Latest changes (v8.1.3)

- **macOS builds are now signed with a Developer ID certificate and notarized by Apple** — they open without Gatekeeper warnings.
- **New app icon** across all desktop platforms — refreshed branding on macOS and Windows.
- **Fixed the Windows installer build** — the icon is now generated as a proper multi-size `.ico` (16–256px) so the installer packages correctly.
- **iOS build 23** uploaded to TestFlight.
- Rebuilt and republished every platform: macOS (ARM + Intel), Windows, Android, and iOS.

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
