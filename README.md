# 🏛️ Open Acts (ActsRead) — Official Releases & Downloads

> **India's Premier Digital Legal Library & Research Platform**

Welcome to the official public distribution repository for **Open Acts**. Here you can find the latest production installers, portable bundles, and release packages for Windows desktop, macOS, iOS, and Android.

---

## 📥 Latest Production Downloads (v2.2.0)

| Platform | Package Type | File Name | Size | Direct Download Link |
| :--- | :--- | :--- | :--- | :--- |
| **Windows** | **Setup Installer (`.exe`)** | `OpenActs-Windows-v2.2.0-Setup.exe` | 16.7 MB | [⬇️ Download Setup](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-Windows-v2.2.0-Setup.exe) |
| **Windows** | **Portable ZIP (`.zip`)** | `OpenActs-Windows-v2.2.0-Portable.zip` | 22.1 MB | [⬇️ Download Portable ZIP](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-Windows-v2.2.0-Portable.zip) |
| **macOS** | **DMG Installer (`.dmg`)** | `OpenActs-macOS-v2.2.0.dmg` | 48.8 MB | [⬇️ Download macOS DMG](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-macOS-v2.2.0.dmg) |
| **macOS** | **Portable Bundle (`.zip`)** | `OpenActs-macOS-v2.2.0.zip` | 42.2 MB | [⬇️ Download macOS ZIP](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-macOS-v2.2.0.zip) |
| **iOS** | **Apple Package (`.ipa`)** | `OpenActs-iOS-v2.2.0-Unsigned.ipa` | 24.4 MB | [⬇️ Download iOS IPA](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-iOS-v2.2.0-Unsigned.ipa) |
| **Android** | **Signed Release APK (`.apk`)** | `OpenActs-Android-v2.2.0.apk` | 63.6 MB | [⬇️ Download Android APK](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-Android-v2.2.0.apk) |
| **Android** | **Google Play Store** | Play Store App | — | *Reserved for Play Store Release* |

---

## ⚡ Highlights & Features

* **Strict Online-Only Architecture:** Always fetches authentic, up-to-date statutory sections and court-ready legal text directly from the cloud.
* **10,930+ Indian Bare Acts:** Complete coverage of Central Enactments and 35 State/UT Jurisdictions.
* **Verbatim Statutory Text:** 100% gazette-grade authentic text for major codes including CPC 1908, IPC 1860, BNS, and special acts.
* **Modern Windows Desktop Experience:** Dual-pane navigation, legal search, and customized reading modes (Light / Dark).
* **Cross-Platform Security:** Hardened with Android App Transport Security / cleartext denial, macOS sandboxing, and Windows DLL preloading mitigation.
* **Fully Standalone & Self-Contained:** The Windows installer bundles all required Microsoft Visual C++ runtime components. No dependencies, VS Code, or Flutter needed on the client computer.

---

## 💻 Installation & Usage Guide

### Windows Installation
1. **Setup Installer (`.exe`)**: Download [OpenActs-Windows-v2.2.0-Setup.exe](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-Windows-v2.2.0-Setup.exe) and double-click to install.
2. **Portable ZIP (`.zip`)**: Download [OpenActs-Windows-v2.2.0-Portable.zip](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-Windows-v2.2.0-Portable.zip), extract, and run `open_acts.exe`.

### Android Installation
1. Download [OpenActs-Android-v2.2.0.apk](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-Android-v2.2.0.apk).
2. Open the downloaded APK on your Android device (allow "Install from unknown sources" if prompted) and tap **Install**.

### macOS Installation
1. Download [OpenActs-macOS-v2.2.0.dmg](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-macOS-v2.2.0.dmg).
2. Double-click to open the DMG, then drag **Open Acts** into the **Applications** folder.

### iOS Sideloading
1. Download [OpenActs-iOS-v2.2.0-Unsigned.ipa](https://github.com/Akshay-Katiyar/open-acts-releases/releases/download/v2.2.0/OpenActs-iOS-v2.2.0-Unsigned.ipa).
2. Install via **AltStore**, **Sideloadly**, or **TrollStore** using your Apple ID.

---

## 🔒 Security & Integrity Verification (SHA-256)

To verify the integrity of your downloaded files, compare the computed SHA256 checksum:

```text
ae901460bfd239bd2b5c8d32658ebe3309905da32f6d87787370a6391d02392a  OpenActs-Windows-v2.2.0-Setup.exe
6b200a82f7e290d40afcb6c9fc043472e89c4eae1894bb2bb2cdca25bf619433  OpenActs-Windows-v2.2.0-Portable.zip
a2338c7e6ede99a0e1fef428430358b71347a49220b2f48aceb9742cf157f896  OpenActs-macOS-v2.2.0.dmg
5ed8caf583f498ada489d661696049f29d7c05375fbde3d959d86cf8bfc67aeb  OpenActs-macOS-v2.2.0.zip
2681d18cf9af7a16065eaea9de7eb410dfe31f6c1fe0b29b102007fbb38a8b08  OpenActs-iOS-v2.2.0-Unsigned.ipa
6f0e859c82faff797cac17c8891c3768c8e703729f546322e9a7e8322198ed14  OpenActs-Android-v2.2.0.apk
```

**PowerShell Verification Command:**
```powershell
Get-FileHash -Algorithm SHA256 "OpenActs-Android-v2.2.0.apk"
```

---

## 📋 System Requirements

* **Windows:** Windows 10 (64-bit) or Windows 11
* **Android:** Android 7.0 (Nougat, API 24) or higher
* **macOS:** macOS 11.0 (Big Sur) or higher
* **iOS:** iOS 14.0 or higher
* **Memory:** 2 GB RAM minimum (4 GB recommended)
* **Storage:** 100 MB available space
* **Network:** Active internet connection (broadband or mobile data)

---

## 📬 Support & Inquiries
For bug reports, feature requests, or legal catalog inquiries, please open an Issue in this repository.
