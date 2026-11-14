<!-- HEADER_START -->
# <img src="../../assets/icons/com.truecaller.png" width="36" height="36" align="top" alt=""> Truecaller

![version](https://img.shields.io/badge/version-26.43.5-2563eb?style=for-the-badge&labelColor=0d1117) ![patches](https://img.shields.io/badge/patches-2-14b8a6?style=for-the-badge&labelColor=0d1117) ![file](https://img.shields.io/badge/file-APKM-0ea5e9?style=for-the-badge&labelColor=0d1117) ![menu](https://img.shields.io/badge/menu-Profile%20menu%20%C2%B7%20Settings-6e7681?style=for-the-badge&labelColor=0d1117)

[← All apps](../../README.md#apps)&nbsp;&nbsp;•&nbsp;&nbsp;`com.truecaller`&nbsp;&nbsp;•&nbsp;&nbsp;[v3.0.0](https://github.com/lokesh-sparrow/loki-patches/releases/tag/v3.0.0)

**🎯 Supported versions:** `26.43.5`
<!-- HEADER_END -->

## Features

| | |
|---|---|
| ⭐ **Premium features** | No ads, premium badge, incognito, ghost call, extended spam blocking, call recording, announce call, family sharing |
| 📵 **No after-call screen** | Skip the screen Truecaller shows when a call ends (switchable) |
| ☁️ **Google sign-in and Drive backup** | Through microG RE (optional patch) |

Features whose content comes from Truecaller's servers (who viewed me, who searched for me, caller ID for unknown
numbers, fraud insurance) open but stay empty.

## FAQ

**Where is the after-call screen switch?**
Loki Patches → **Calls**. It applies from the next call; no restart needed.

**Where is the Loki Patches entry?**
In the profile menu and in **Settings**, where Truecaller showed its Android watch entry.

## Patches

<!-- PATCHES_START -->
| 💊&nbsp;Patch | 📜&nbsp;Description | ⚙️&nbsp;Options |
|---|---|---|
| **Enable premium features (Truecaller)** | Makes every premium feature the app decides on the device available, and the plan read as active instead of Free, and stops the after-call screen. Features whose content comes from Truecaller's servers (who viewed me, caller ID for unknown numbers, fraud insurance) open but stay empty - their data is not in the app. |  |
| **GmsCore support (Truecaller)** | Routes Google sign-in, the Google Drive backup of contacts and call logs, and Firebase push through MicroG-RE (GmsCore) instead of Google Play services. Signs the FCM registration with Truecaller's original certificate, so notifications still arrive on a re-signed build. MicroG-RE has to be installed and signed in to a Google account. |  |
<!-- PATCHES_END -->
