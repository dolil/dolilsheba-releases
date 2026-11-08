<p align="center">
  <img src="logo.svg" alt="SDMS" width="104" height="104">
</p>

<h1 align="center">Smart Deed Management System (SDMS)</h1>

<p align="center">
  <strong>স্মার্ট দলিল ম্যানেজমেন্ট সিস্টেম</strong><br><br>
  An <strong>AI-powered</strong> platform for the preparation and management of land deeds in Bangladesh.<br>
  Documents scanned with the SDMS mobile app are read by AI and entered directly into the deed.
</p>

<p align="center">
  <a href="https://github.com/dolil/dolilsheba-releases/releases/latest"><img src="https://img.shields.io/github/v/release/dolil/dolilsheba-releases?label=Windows&color=16a34a&style=for-the-badge&logo=windows&logoColor=white" alt="Latest Windows release"></a>
  <a href="https://github.com/dolil/dolilsheba-mobile-releases/releases/latest"><img src="https://img.shields.io/github/v/release/dolil/dolilsheba-mobile-releases?label=Android&color=16a34a&style=for-the-badge&logo=android&logoColor=white" alt="Latest Android release"></a>
  <a href="https://github.com/dolil/dolilsheba-releases/releases"><img src="https://img.shields.io/github/downloads/dolil/dolilsheba-releases/total?label=Downloads&color=15803d&style=for-the-badge" alt="Total downloads"></a>
</p>

<p align="center">
  <a href="https://dolil.github.io/dolilsheba-releases/"><strong>Download Page</strong></a>
  &nbsp;·&nbsp;
  <a href="https://dolilsheba.com">Website</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/dolil/dolilsheba-releases/releases">Release History</a>
</p>

---

## Download

| Component | Platform | Download |
|---|---|---|
| **Desktop Software** | Windows 10 / 11 (64-bit) | [**Windows Installer (.exe)**](https://dolil.github.io/dolilsheba-releases/) |
| **Mobile Application** | Android 7.0 or later | [**Android Application (.apk)**](https://github.com/dolil/dolilsheba-mobile-releases/releases/latest/download/dolilsheba.apk) |

The [download page](https://dolil.github.io/dolilsheba-releases/) always provides the latest
version of both components, together with their release notes.

## Overview

### Desktop Software (Windows)

The primary application for deed preparation, designed for deed writers, legal practitioners,
real estate firms and banking institutions.

- **AI-assisted data entry:** party and land details are populated automatically from scanned documents
- **32 deed types**, with prepared templates for all commonly used property deeds
- Print-ready output in the appropriate legal format
- **Offline operation:** deeds can be prepared and printed without an internet connection;
  connectivity is required only for licensing and synchronisation
- Synchronisation of **নকল, তল্লাশ ও এলটি নোটিশ** between the desktop and the web platform
- Mouza and deed-writer directories are kept current from the server automatically
- All deed records are stored locally on the user's computer
- **Automatic updates:** new versions are downloaded and installed in a single step

### Mobile Application (Android)

The mobile application operates in conjunction with the desktop software and removes the need
for manual data entry.

- **দলিলসেবা AI document scanning:** capture the National ID cards of the parties and scan the
  QR code of a দাখিলা or নামজারি খতিয়ান
- **Direct transfer to the desktop:** names, addresses, দাগ and খতিয়ান numbers are extracted
  and delivered to the corresponding step of the open deed, where the user reviews them and
  confirms with **যোগ করুন**
- **Reference services:** market values, mouza directory, laws and regulations, sample forms,
  office directory and document verification
- Automatic updates from the official release channel

### Workflow

| Step | Device | Action |
|:---:|---|---|
| 1 | Mobile | Scan the QR code displayed in the **মোবাইল স্ক্যান** section of the deed to link the device |
| 2 | Mobile | Capture the National ID cards and scan the দাখিলা or খতিয়ান |
| 3 | Mobile → Desktop | AI extracts the relevant details and transmits them to the deed |
| 4 | Desktop | Review the extracted details, confirm with **যোগ করুন**, and print |

## Installation

### Windows

1. Open the [download page](https://dolil.github.io/dolilsheba-releases/) and select
   **Windows সংস্করণ ডাউনলোড করুন**. The installer is named `dolilsheba-Setup-x.y.z.exe`.
2. Run the installer and follow the on-screen instructions.
3. If Windows displays **"Windows protected your PC"**, select **More info → Run anyway**.
4. Launch the software from the desktop shortcut and sign in.

### Android

1. On the mobile device, download the
   [Android application](https://github.com/dolil/dolilsheba-mobile-releases/releases/latest/download/dolilsheba.apk).
2. Open the downloaded file. On first installation, Android requests permission to
   **install from this source**; grant the permission and select **Install**.
3. Launch the application, sign in, and scan the QR code shown in the **মোবাইল স্ক্যান**
   section of the desktop software to link the device to a deed.

## System Requirements

| | Desktop Software | Mobile Application |
|---|---|---|
| Operating system | Windows 10 or 11, 64-bit | Android 7.0 or later |
| Storage | Approximately 200 MB | Approximately 90 MB (download) |
| Internet | Sign-in, licensing, synchronisation and updates | Document scanning and transfer to the desktop |

## Updates

Both components check for new versions automatically.

- **Desktop software:** an update notification is shown within the application. Updates may
  also be checked manually via **Help → Check for Updates**.
- **Mobile application:** the user is notified when a new version is available, and the update
  is installed from the official release channel.

Release notes for each version are published on the
[desktop releases](https://github.com/dolil/dolilsheba-releases/releases) and
[mobile releases](https://github.com/dolil/dolilsheba-mobile-releases/releases) pages.

## Download Verification

The SHA-256 checksum of each Android package is published in its release notes and on the
download page. All Android packages are signed with the same key; the signing certificate's
SHA-256 fingerprint is:

```
d368f1219204e7beb6589b12455c66347516b64736ed0763ec6e0e6b6560ac83
```

Installers should be obtained only from this repository, the
[mobile releases](https://github.com/dolil/dolilsheba-mobile-releases) repository, or
[dolilsheba.com](https://dolilsheba.com).

## Support

- Website: [dolilsheba.com](https://dolilsheba.com)
- Email: [dolilsheba@gmail.com](mailto:dolilsheba@gmail.com) · [info@dolilsheba.com](mailto:info@dolilsheba.com)

## About This Repository

This repository contains **release files only**; no source code is hosted here. All releases
are built and published through an automated pipeline.

<details>
<summary>Download page maintenance</summary>

`index.html` is published through GitHub Pages at <https://dolil.github.io/dolilsheba-releases/>.
It reads two generated files, which should not be edited manually:

- `latest.json`: the most recent published desktop release of this repository
- `mobile.json`: a copy of `latest.json` from the most recent release of
  [`dolil/dolilsheba-mobile-releases`](https://github.com/dolil/dolilsheba-mobile-releases)

[`.github/workflows/update-latest.yml`](.github/workflows/update-latest.yml) regenerates both
files on every release event in this repository and on an hourly schedule, which captures new
Android releases. The page falls back to the GitHub API only when `latest.json` is unavailable,
as anonymous API access is limited to 60 requests per hour per IP address.

</details>

---

<p align="center">
  Developed and maintained by <strong>Upakul Dolil Sheba</strong>, Sylhet, Bangladesh.<br>
  <sub>© 2024–2026 Upakul Dolil Sheba. All rights reserved.</sub>
</p>
