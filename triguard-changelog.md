# TriGuard Core Changelog

## v1.0-Stable (Universal Production Release)
- **Branding & Isolation:** Assigned unique reverse-domain module ID `in.pramodkumar.triguardcore` and title `TriGuard Core — Data, Icon & Audio Control`.
- **NetVault:** Added foreground-only iptables/ip6tables firewall with instant per-app background allow toggles and screen-off lockdown.
- **IconCloak (Universal Launcher Support):** Added multi-activity launcher detection and an active auto-relock watcher (`enforce_iconcloak`) so Home button presses on Vivo (Funtouch OS), OnePlus (OxygenOS), Oppo (ColorOS), Realme, Xiaomi, Samsung, and Pixel launchers never unhide locked apps.
- **SoundHold:** Added strict per-stream volume locker (Call, Ring with ringer-mode enforcement, Media, Notification, Alarm) plus Lock All / Unlock All controls.
- **Safety & Diagnostics:** Added passive anti-bootloop self-guard (auto-disables after 2 incomplete boots without affecting other modules) and live diagnostic reporting via the Magisk Action button.
