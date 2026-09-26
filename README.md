# Nexus Deck

**Your PC. In your hand.**

Nexus Deck pairs your Android phone with your Windows PC over your own network:
live system telemetry, media and volume control, file transfers, game launching,
and remote actions — private by design, no accounts, no cloud.

## Downloads

| Platform | Download |
|---|---|
| **Windows** | [Nexus-Deck-Setup.exe](https://github.com/ayaan-is-ak/nexus-deck/releases/latest/download/Nexus-Deck-Setup.exe) — tiny installer, everything else downloads automatically |
| **Android** | [Nexus-Deck.apk](https://github.com/ayaan-is-ak/nexus-deck/releases/latest/download/Nexus-Deck.apk) — sideload onto your phone |

> Android: allow "install unknown apps" for your browser/file manager once,
> then open the APK and confirm.

## Install (Windows)

1. Download **Nexus-Deck-Setup.exe** and run it — no admin rights needed.
2. Accept the terms, pick a location, hit **INSTALL**.
3. A welcome page opens; the app appears in your Start Menu and Desktop.

On first launch a short setup walks you through naming your PC and shows a
**pairing code** — enter/pair it from the Nexus Deck app on your phone and
you're connected.

## Requirements

- Windows 10 (1809+) or Windows 11 — 64-bit
- Android 8.0+ phone on the same Wi-Fi network
- ~400 MB disk space for the PC app

## Staying up to date

Updates are delivered through the paired PC. When the developer publishes an
update, the desktop app tells your phone, shows what's new, and installs it —
you confirm once and the app takes care of the rest.

## Privacy

- Everything runs on **your own network** — no accounts, no cloud, no telemetry leaves your home.
- Pairing uses encrypted per-device tokens stored only on your PC.
- Uninstalling removes everything; the farewell page erases itself when you close it.

## Verify your download (optional)

Checksums for every release artifact are published alongside the files in
`SHA256SUMS.txt`. On Windows:

```powershell
Get-FileHash .\Nexus-Deck-Setup.exe -Algorithm SHA256
```

Compare the output with the matching line in `SHA256SUMS.txt` from the same release.

---
Nexus Deck © 2026 · built with ♥ and zero cloud dependency
