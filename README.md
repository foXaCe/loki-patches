<p align="center">
  <img src=".github/assets/header.jpg" alt="Loki Patches: No Ads. No Clutter. Open-source Morphe patches" width="100%">
</p>

<div align="center">

[![Latest release](https://img.shields.io/github/v/release/lokesh-sparrow/loki-patches?sort=semver&style=for-the-badge&label=release&labelColor=0d1117&color=22d3ee)](https://github.com/lokesh-sparrow/loki-patches/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/lokesh-sparrow/loki-patches/total?style=for-the-badge&labelColor=0d1117&color=0ea5e9)](https://github.com/lokesh-sparrow/loki-patches/releases)
[![Apps](https://img.shields.io/badge/apps-4-2563eb?style=for-the-badge&labelColor=0d1117)](#patches)
[![Morphe](https://img.shields.io/badge/patches%20for-Morphe-06b6d4?style=for-the-badge&labelColor=0d1117)](https://morphe.software)
[![License](https://img.shields.io/github/license/lokesh-sparrow/loki-patches?style=for-the-badge&labelColor=0d1117&color=6e7681)](LICENSE)

<br/>

[**Features**](#features) · [**Install**](#install) · [**Settings**](#settings) · [**FAQ**](#faq) · [**Report a bug**](https://github.com/lokesh-sparrow/loki-patches/issues/new/choose)

<br/>

<a href="https://morphe.software/add-source?github=lokesh-sparrow/loki-patches&name=Loki%20Patches"><img src=".github/assets/add-to-morphe.svg" alt="Add to Morphe" height="55"/></a>

<sub>Stable releases. One source for <b>LinkedIn</b>, <b>Splitwise</b>, <b>Truecaller</b> and <b>Doc Scanner</b>. Turn off Play Store auto-update for the apps you patch, or it replaces them.</sub>

</div>

> [!NOTE]
> Built and maintained by **Lokesh Sparrow**. You patch the apps on your own phone with Morphe Manager;
> nothing is sent anywhere. Not affiliated with LinkedIn, Splitwise, Truecaller, Doc Scanner or the Morphe project.
>
> **Already using Loki Patches for LinkedIn?** Nothing changes for you: same source, same patches, same settings.
> Update in Morphe Manager as usual.

---

## Features

### LinkedIn

| | |
|---|---|
| ✂️ **Copy text** | Long press any post, comment or profile text to select and copy it, right where it is |
| 🚫 **No ads** | Promoted posts, promoted jobs, Premium and AI upsells, sponsored messages |
| ⬇️ **Downloads** | Photos and videos in full screen (one or **all** of a post), profile photos and banners, in the best quality |
| 📄 **Documents as PDF** | Save a post's document or carousel as one PDF file |
| 🧹 **Feed filters** | Focus mode, and hide suggested posts, celebrations, job cards, network activity, videos, AI suggestions and more |
| 🕵️ **Anonymous profile viewing** | Visit profiles without showing up in their "Who viewed your profile" (experimental) |
| 👻 **Ghost mode** | Chat without the typing indicator or automatic read receipts |
| 🔗 **Clean links** | Open outside links directly, strip tracking from links you share |
| 🛡️ **Block tracking** | Stop most of LinkedIn's analytics |
| 🎨 **Material You** | Your wallpaper's colors, and an optional flat feed without gaps |
| ⚫ **AMOLED black bars** | Pure black top bar, bottom bar and side menu in dark mode (needs Material You) |
| 🖤 **Dark app icon** | Black launcher icon with the white "in", instead of LinkedIn's blue (optional) |
| 👆 **Swipe between feeds** | Swipe left or right to switch For you and Network, and Grow and Catch up |
| 🖼️ **Tap to hide in viewers** | Tap a document or video in full screen to hide its caption and buttons |
| ⋯ **Post menu items** | Copy text, Download media and Save as PDF in a post's menu |
| 🧭 **Hide bottom tabs** | Take My Network and Jobs out of the bottom bar |
| 🔑 **Google sign-in** | "Continue with Google" through microG RE |

### Splitwise

| | |
|---|---|
| ⭐ **Pro features** | Unlimited expenses, receipt scanning, charts, search, currency conversion, itemization, default splits, totals history and export |
| 🚫 **No Pro upsells** | The "Get Pro" cards, banners and Pro rows are gone |
| ⚫ **AMOLED black** | Real black in dark mode, switchable in the Loki Patches menu |
| 🔑 **Google sign-in** | Through microG RE (optional patch) |

### Truecaller

| | |
|---|---|
| ⭐ **Premium features** | No ads, premium badge, incognito, ghost call, extended spam blocking, call recording, announce call, family sharing |
| 📵 **No after-call screen** | Skip the screen Truecaller shows when a call ends (switchable) |
| ☁️ **Google sign-in and Drive backup** | Through microG RE (optional patch) |

Features whose content comes from Truecaller's servers (who viewed me, who searched for me, caller ID for unknown
numbers, fraud insurance) open but stay empty.

### Doc Scanner

| | |
|---|---|
| ⭐ **Full version** | Premium unlocked |
| 🧹 **Declutter** | Promotions and "follow us" clutter removed |
| 👯 **Allow clone** | Works next to the original when installed with a changed package name |
| 🔑 **Google sign-in** | Cloud sign-in through microG RE (optional patch) |

### Every app

The **Loki Patches menu**: patch status, settings backup to a file, diagnostics with a shareable bug report, the
update check, and an optional app-drawer icon. It is inside each app (see [Settings](#settings)).

### Anonymous profile viewing

Visit a profile without it appearing in that member's "Who viewed your profile", or in company page visitor lists.

1. Turn on **Anonymous profile viewing** in the Loki Patches settings, under **Privacy**. It is off by default and
   marked experimental.
2. Open profiles as usual. The app leaves out the analytics events that profile pages send, so the visit is not counted.

It works by not sending those events, not by hiding the visit on the server. LinkedIn can change what a profile page
sends in any update; if a visit still appears, please report it with the diagnostic log.

### Copy text

LinkedIn doesn't let you copy what people write. With Loki Patches you can:

1. **Long press** any text: a post, a comment, a profile's About, a job description.
2. The word under your finger is selected **right where it is**, with Android's selection handles and
   the **Copy · Select all · Share** bar, the same as in any other app.
3. Drag the handles to select more. On posts cut off by "…more", the bar also has **Copy full text**.
4. Tap anywhere to go back.

Long presses that already do something in LinkedIn, like the reaction button, keep working as before.
A tap or a scroll works as usual.

## Install

You need an Android phone and [Morphe Manager](https://morphe.software).

1. In Morphe Manager, **[add the Loki Patches source](https://morphe.software/add-source?github=lokesh-sparrow/loki-patches&name=Loki%20Patches)**
   (or add `https://github.com/lokesh-sparrow/loki-patches` by hand). It gets stable releases only.
2. Choose the app, and download the version Morphe Manager recommends from APKMirror:

   | App | Download |
   |---|---|
   | LinkedIn | the *Android 10+* plain **APK** (the bundle variants cannot be patched) |
   | Splitwise | the plain **APK** |
   | Truecaller | the **APKM** bundle |
   | Doc Scanner | the **APKM** bundle |

3. Patch it and install it.

Use one patch source per app. If you add another source for the same app, or keep an older copy of this one,
switch it off in Manager first: picking the same patches from two sources applies them twice and the result may
not install.

## Settings

Every app gets the same **Loki Patches** menu. Open it from inside the app, or by long pressing the app's icon on
your home screen:

| App | Inside the app |
|---|---|
| LinkedIn | **Me** panel (tap your profile photo) |
| Splitwise | **Account** tab |
| Truecaller | profile menu, or **Settings**: the **Loki Patches** entry with the puzzle icon |
| Doc Scanner | side menu |

The menu has the app's own pages, then the same pages everywhere: **Patch status**, **Backup & restore** (save your
settings to a file you choose, and restore it, even after reinstalling), **Diagnostics**, **General** and **About**.
LinkedIn's menu also has search and the language picker.

> [!IMPORTANT]
> Please don't share patched APKs. Share this source instead, so everyone gets the latest fixes.

## Patches

<!-- PATCHES_START EXPANDED -->
> **[v3.0.0](https://github.com/lokesh-sparrow/loki-patches/releases/tag/v3.0.0)**&nbsp;&nbsp;•&nbsp;&nbsp;`main`&nbsp;&nbsp;•&nbsp;&nbsp;36 patches total
<details open>
<summary><img src="assets/icons/com.Splitwise.SplitwiseMobile.png" width="20" height="20" align="top" alt=""> Splitwise&nbsp;&nbsp;•&nbsp;&nbsp;5 patches</summary>
<br>

**🎯 Supported versions:**

| 26.11.1 |
| :---: |

| 💊&nbsp;Patch | 📜&nbsp;Description | ⚙️&nbsp;Options |
|----------|----------------|-----------|
| [AMOLED black (Splitwise)](#amoled-black-splitwise) | Real black instead of dark grey in Splitwise's dark mode: backgrounds, screens, bottom sheets, the status and navigation bars and the group charts. Cards stay a shade lighter so they stand out. AMOLED screens switch black pixels off, which saves battery. Light mode is unchanged. Can be switched off in Loki Patches > Appearance. |  |
| [Enable premium features (Splitwise)](#enable-premium-features-splitwise) | Treats the account as Pro and switches on the paid features: unlimited expense entries, search, charts, spreadsheet export, currency conversion, group totals history and stats, default splits, reminders, balance alerts, trip dates, larger receipt images and itemization. |  |
| [GmsCore support (Splitwise)](#gmscore-support-splitwise) | MicroG-RE integration for Splitwise: routes Google sign-in and Google Drive through MicroG-RE instead of Google Play services, and keeps ML Kit's module loader on real Play services so receipt OCR keeps working. MicroG-RE has to be installed and signed in to a Google account. |  |
| [Hide Pro ads and upsells](#hide-pro-ads-and-upsells) | Removes the full-screen ad after adding an expense, the ad in Activity, the Pro diamond, the Pro account and Pro Duo cards, the Pro Pass prompts, the Pro tour screen, the hiring promo and the rate-the-app prompt. |  |
| [Remove analytics and crash reporting](#remove-analytics-and-crash-reporting) | Turns off Firebase Analytics, Crashlytics and the advertising-ID collection the app declares in its manifest. |  |

</details>

<details open>
<summary><img src="assets/icons/com.linkedin.android.svg" width="20" height="20" align="top" alt=""> LinkedIn&nbsp;&nbsp;•&nbsp;&nbsp;23 patches</summary>
<br>

**🎯 Supported versions:**

| 4.1.1267 | 4.1.1269 | 4.1.1270 |
| :---: | :---: | :---: |

| 💊&nbsp;Patch | 📜&nbsp;Description | ⚙️&nbsp;Options |
|----------|----------------|-----------|
| [AMOLED black bars](#amoled-black-bars) | Turns the dark top bar, bottom bar, side menu and the other screens the app draws pure black, matching the feed that the AMOLED black setting already covers. Needs Material You. |  |
| [Anonymous profile viewing](#anonymous-profile-viewing) | Adds an option (off by default, experimental) to visit profiles without being listed in "Who viewed your profile": the analytics events of profile pages are not sent. |  |
| [Block tracking](#block-tracking) | Adds a switch (off by default) that stops most of LinkedIn's analytics events from being sent. |  |
| [Copy text](#copy-text) | Long press a post, comment or any other text to select and copy it in place, like on Reddit. |  |
| [Dark app icon](#dark-app-icon) | Black launcher icon with the white "in", instead of LinkedIn's blue. Chosen when patching: a launcher icon cannot switch with dark mode on its own. |  |
| [Disable double-tap like](#disable-double-tap-like) | A double tap on a post or a photo no longer likes it. |  |
| [Download media](#download-media) | Puts a download button in the full screen photo, video and document viewer; documents (PDFs and carousels) are saved as a single PDF. |  |
| [Feed filters](#feed-filters) | Adds a set of filters that are off until turned on in Loki Patches: focus mode, celebrations, job cards, reposts, posts from other people's activity, "Recommended for you", video posts, games, the "New posts" pill and "See translation". |  |
| [GmsCore support](#gmscore-support) | Routes "Continue with Google" and Firebase push through MicroG-RE (GmsCore) instead of Google Play services. Signs the FCM registration with LinkedIn's original certificate, so notifications still arrive on a re-signed build. MicroG-RE has to be installed and signed in to a Google account. |  |
| [Hide Premium upsells](#hide-premium-upsells) | Drops the Premium and AI upsell cards and banners, on profiles and in the Me panel too. |  |
| [Hide ads](#hide-ads) | Removes sponsored (promoted) posts from the feed. |  |
| [Hide bottom tabs](#hide-bottom-tabs) | Adds switches to take My Network and Jobs out of the bottom bar. |  |
| [Hide promoted jobs](#hide-promoted-jobs) | Drops promoted job listings from the Jobs tab and from job searches. |  |
| [Hide suggested posts](#hide-suggested-posts) | Drops the "Suggested" posts from people outside your network. |  |
| [Keep feed on reopen](#keep-feed-on-reopen) | Keeps your place in the feed when you come back to LinkedIn, instead of reloading it. Pull down or tap the "New posts" button to load new posts. |  |
| [Material You](#material-you) | Takes the colors from your wallpaper (Android 12+): the accent replaces LinkedIn blue and the green of the selected filters, and the backgrounds, cards, bars and borders become Material 3 surfaces. Some screens LinkedIn draws from its servers may keep their own colors. |  |
| [Messaging](#messaging) | Drops sponsored messages from the inbox, and adds an optional ghost mode that sends no typing indicators and no read receipts. |  |
| [Open links directly](#open-links-directly) | Skips LinkedIn's safety/go warning page and opens external links straight away. |  |
| [Post menu items](#post-menu-items) | Adds Copy text, Download photos and videos, and Save document as PDF to the ⋯ menu of posts. |  |
| [Remove gaps and dividers](#remove-gaps-and-dividers) | Removes the gray gaps between posts and the dividers between list items, so the feed and the lists read as one flat surface. |  |
| [Sanitize share links](#sanitize-share-links) | Strips the tracking parameters from LinkedIn links that get copied or shared. |  |
| [Swipe between feeds](#swipe-between-feeds) | Swipe left and right on the home feed to switch between For you and Network, like on X. |  |
| [Tap to hide in viewers](#tap-to-hide-in-viewers) | Tap a video or document in full screen to hide the caption and buttons, like photos. |  |

</details>

<details open>
<summary><img src="assets/icons/com.cv.docscanner.png" width="20" height="20" align="top" alt=""> Doc Scanner&nbsp;&nbsp;•&nbsp;&nbsp;4 patches</summary>
<br>

**🎯 Supported versions:**

| 6.9.9 |
| :---: |

| 💊&nbsp;Patch | 📜&nbsp;Description | ⚙️&nbsp;Options |
|----------|----------------|-----------|
| [Allow clone](#allow-clone) | Lets the app run under a package name made by the Change package name patch: the app compares its own package name with the original at start-up and shuts itself down when they differ. |  |
| [Declutter](#declutter) | Removes the promo banner on the home screen and the cross-promotion and cloud-login cards on the save-success screen. |  |
| [Enable premium features](#enable-premium-features) | Turns on the app's paid features (unlimited scans, cloud upload, OCR, PDF passwords, compression, signatures, themes). The app skips its ad slots for paid users, so the ads go away with them. |  |
| [GmsCore support (Doc Scanner)](#gmscore-support-doc-scanner) | MicroG-RE integration for Doc Scanner: routes Google sign-in and Google Drive through MicroG-RE instead of Google Play services, and keeps ML Kit's module loader on real Play services so receipt OCR keeps working. MicroG-RE has to be installed and signed in to a Google account. |  |

</details>

<details open>
<summary><img src="assets/icons/com.truecaller.png" width="20" height="20" align="top" alt=""> Truecaller&nbsp;&nbsp;•&nbsp;&nbsp;2 patches</summary>
<br>

**🎯 Supported versions:**

| 26.43.5 |
| :---: |

| 💊&nbsp;Patch | 📜&nbsp;Description | ⚙️&nbsp;Options |
|----------|----------------|-----------|
| [Enable premium features (Truecaller)](#enable-premium-features-truecaller) | Makes every premium feature the app decides on the device available, and the plan read as active instead of Free, and stops the after-call screen. Features whose content comes from Truecaller's servers (who viewed me, caller ID for unknown numbers, fraud insurance) open but stay empty - their data is not in the app. |  |
| [GmsCore support (Truecaller)](#gmscore-support-truecaller) | Routes Google sign-in, the Google Drive backup of contacts and call logs, and Firebase push through MicroG-RE (GmsCore) instead of Google Play services. Signs the FCM registration with Truecaller's original certificate, so notifications still arrive on a re-signed build. MicroG-RE has to be installed and signed in to a Google account. |  |

</details>

<details open>
<summary>🌐 Universal&nbsp;&nbsp;•&nbsp;&nbsp;2 patches</summary>
<br>

| 💊&nbsp;Patch | 📜&nbsp;Description | ⚙️&nbsp;Options |
|----------|----------------|-----------|
| [Change package name](#change-package-name) | Changes the package name by adding a suffix (".loki" by default), so the patched app installs next to the original app instead of replacing it. Some apps check their own package name and need a small extra patch to run under the new one. | • Package suffix |
| [Remove ads and trackers](#remove-ads-and-trackers) | Removes ads, analytics and crash reporting, and the advertising ID. | • Ads<br>• Analytics and crash reporting<br>• Advertising ID |

</details>

<!-- PATCHES_END -->

## FAQ

**How do I stop videos playing on their own, or hide that I'm online?**
LinkedIn has its own settings for both, and Loki Patches leaves them to LinkedIn: **Settings → Account preferences →
Autoplay videos → Never**, and **Settings → Visibility → Manage active status → No one**.

**Is anonymous profile viewing reliable?**
It's experimental. It stops the app from sending the analytics events of profile pages, which is how LinkedIn
counted visits in our tests on 4.1.1270. LinkedIn could change that in an update. If someone still sees you, please
report it.

**I can't find the Loki Patches menu.**
The home screen shortcut only appears once the app has been opened at least once, and some launchers hide
shortcuts entirely, so use the entry inside the app instead (see [Settings](#settings)), or switch on
**General → Show in the app drawer**. If the entry is missing there as well, confirm on the
[patches list](#patches) that your LinkedIn version is supported, and attach a diagnostic report.

**I can't sign in with Google.**
Google checks the app's signature, so signing in with Google needs the **GmsCore support** patch and
[microG RE](https://github.com/MorpheApp/microg-RE) installed and signed in to your Google account. Signing
in with your e-mail and password always works. If you signed up with Google and have no password, set one
on [linkedin.com](https://www.linkedin.com/checkpoint/rp/request-password-reset) first.

**Material You or AMOLED black doesn't change some screens.**
The colors are read when the app is patched, and a few older screens in LinkedIn keep the ones they were
built with. Restarting LinkedIn after a change is still worth it, but those screens stay as they are.

## Reporting a bug

In the Loki Patches menu, open **Diagnostics**, switch on **Diagnostic logging**, reproduce the problem, then use
**Copy report** (or **Share report**) and paste the text into a [bug report](https://github.com/lokesh-sparrow/loki-patches/issues/new/choose).
Say which app it is about.
Anything that could identify you (links, IDs, e-mail addresses) is filtered out of the report before it is copied.

## Building from source

You need JDK 17 or newer, the Android SDK, and a GitHub token with `read:packages` in `GITHUB_ACTOR` and
`GITHUB_TOKEN` (Morphe's build tools are on GitHub Packages).

1. Run `./gradlew buildAndroid`.
2. The patch bundle is `patches/build/libs/patches-*.mpp`.
3. Patch with [Morphe Desktop](https://github.com/MorpheApp/morphe-desktop) or Morphe Manager.

## Disclaimer

Loki Patches is an independent project. Neither LinkedIn nor the Morphe project made it, endorses it or is
involved in it. It removes ads and clutter and adds features.
Modifying an app can conflict with that app's terms of service, and you install the result at your own risk.

## License

Loki Patches © 2026 Lokesh Sparrow. Free and open-source software under [GPLv3](LICENSE), with additional project terms and third-party attributions in [NOTICE](NOTICE).

---

<p align="center">
  Built and maintained by <b>Lokesh Sparrow</b> —
  questions or issues? <a href="https://github.com/lokesh-sparrow/loki-patches/issues">Open an issue</a>.
</p>
