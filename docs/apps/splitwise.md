<!-- HEADER_START -->
# <img src="../../assets/icons/com.Splitwise.SplitwiseMobile.png" width="36" height="36" align="top" alt=""> Splitwise

![version](https://img.shields.io/badge/version-26.11.1-2563eb?style=for-the-badge&labelColor=0d1117) ![patches](https://img.shields.io/badge/patches-5-14b8a6?style=for-the-badge&labelColor=0d1117) ![file](https://img.shields.io/badge/file-APK-0ea5e9?style=for-the-badge&labelColor=0d1117) ![menu](https://img.shields.io/badge/menu-Account%20tab-6e7681?style=for-the-badge&labelColor=0d1117)

[← All apps](../../README.md#apps)&nbsp;&nbsp;•&nbsp;&nbsp;`com.Splitwise.SplitwiseMobile`&nbsp;&nbsp;•&nbsp;&nbsp;[v3.0.0](https://github.com/lokesh-sparrow/loki-patches/releases/tag/v3.0.0)

**🎯 Supported versions:** `26.11.1`
<!-- HEADER_END -->

## Features

| | |
|---|---|
| ⭐ **Pro features** | Unlimited expenses, receipt scanning, charts, search, currency conversion, itemization, default splits, totals history and export |
| 🚫 **No Pro upsells** | The "Get Pro" cards, banners and Pro rows are gone |
| ⚫ **AMOLED black** | Real black in dark mode, switchable in the Loki Patches menu |
| 🔑 **Google sign-in** | Through microG RE (optional patch) |

## FAQ

**Where is the AMOLED switch?**
Loki Patches → **Appearance**. Restart Splitwise after changing it.

## Patches

<!-- PATCHES_START -->
| 💊&nbsp;Patch | 📜&nbsp;Description | ⚙️&nbsp;Options |
|---|---|---|
| **AMOLED black (Splitwise)** | Real black instead of dark grey in Splitwise's dark mode: backgrounds, screens, bottom sheets, the status and navigation bars and the group charts. Cards stay a shade lighter so they stand out. AMOLED screens switch black pixels off, which saves battery. Light mode is unchanged. Can be switched off in Loki Patches > Appearance. |  |
| **Enable premium features (Splitwise)** | Treats the account as Pro and switches on the paid features: unlimited expense entries, search, charts, spreadsheet export, currency conversion, group totals history and stats, default splits, reminders, balance alerts, trip dates, larger receipt images and itemization. |  |
| **GmsCore support (Splitwise)** | MicroG-RE integration for Splitwise: routes Google sign-in and Google Drive through MicroG-RE instead of Google Play services, and keeps ML Kit's module loader on real Play services so receipt OCR keeps working. MicroG-RE has to be installed and signed in to a Google account. |  |
| **Hide Pro ads and upsells** | Removes the full-screen ad after adding an expense, the ad in Activity, the Pro diamond, the Pro account and Pro Duo cards, the Pro Pass prompts, the Pro tour screen, the hiring promo and the rate-the-app prompt. |  |
| **Remove analytics and crash reporting** | Turns off Firebase Analytics, Crashlytics and the advertising-ID collection the app declares in its manifest. |  |
<!-- PATCHES_END -->
