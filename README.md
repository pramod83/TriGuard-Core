# TriGuard Core — Data, Icon & Audio Control

**Status:** Stable Production Release (`v1.0-Stable` | Tested on Android 16 / Magisk / KernelSU / APatch)

An open-source, unified Android root control suite by **Pramod Kumar** featuring three independent, zero-conflict engines in one WebUI:
1. **NetVault (Foreground Data Firewall):** Restricts mobile data and Wi-Fi exclusively to the currently active foreground app, plus any user-allowed background apps.
2. **IconCloak (Universal Launcher Icon Hider):** Hides all launcher activities of selected apps across Vivo (Funtouch OS), OnePlus (OxygenOS), Oppo (ColorOS), Realme, Xiaomi, Samsung, and Pixel launchers with an active auto-relock watcher so Home button presses never unhide your apps.
3. **SoundHold (Strict Per-Stream Audio Lock):** Independently lock or unlock Call, Ring (with strict ringer-mode lock), Media, Notification, and Alarm volume levels with individual lock icons plus **Lock all** / **Unlock all** controls.

## Safety & Built-In Protections
* **Passive Anti-Bootloop Self-Guard:** Tracks only TriGuard Core's own state (`/data/adb/triguard_boot.state`) without touching other modules, automatically disabling itself if 2 consecutive boots fail before completion.
* **Live Diagnostic Action Button:** Tapping **Action** in Magisk Manager displays live status for the background service, NetVault firewall rules, locked hidden icons, and locked audio streams.
* **In-App OTA Updates:** Linked via `pk-triguard-ota.json` for seamless Magisk Manager updates.

## Installation
1. Flash `TriGuard-Core-v1.0-Stable.zip` in **Magisk** (v20.4+), **KernelSU**, or **APatch**.
2. **Reboot** your device.
3. Open **KSUWebUIStandalone** or **MMRL** to configure **NetVault**, **IconCloak**, and **SoundHold**.

## License
Released under the [MIT License](LICENSE) — Copyright (c) 2026 Pramod Kumar.
