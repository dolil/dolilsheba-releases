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
  <a href="https://dolil.github.io/dolilsheba-releases/mobile-app/">Mobile App</a>
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
| **Mobile Application** | Android 7.0 or later | [**Android Application (.apk)**](https://github.com/dolil/dolilsheba-mobile-releases/releases/latest/download/dolilsheba.apk) · [details](https://dolil.github.io/dolilsheba-releases/mobile-app/) |

The [download page](https://dolil.github.io/dolilsheba-releases/) always provides the latest
version of both components, together with their release notes.

## Overview

### Desktop Software (Windows)

The primary application for deed preparation, designed for deed writers, legal practitioners,
real estate firms and banking institutions.

- **AI-assisted data entry:** party and land details are populated automatically from scanned documents
- **More than 35 deed types** across transfer, power of attorney, agreement and mortgage, cancellation,
  declaration, lease and trust categories (e.g. সাফ-কবলা, দানপত্র, হেবা, বণ্টননামা, বায়নাপত্র)
- **তল্লাশ/পরিদর্শন (ফরম ১৫৩৫), নকল (ফরম ১৫৮০) and এলটি নোটিশ (ফরম নং-৪)** with fee statements
- Direct printing on stamp paper, stamp + cartridge, full cartridge and certified-copy layouts;
  the installer adds a "Stamp Paper" page size to Windows
- "দ্রুত দলিল" single-page entry, a step-by-step deed wizard, and Bijoy-encoded text paste
- **Offline operation:** after the first sign-in on a computer, deeds and applications can be
  prepared, edited and draft-printed without an internet connection; final prints work offline with
  offline credit or an activated lifetime package. Changes sync automatically once online
- Cloud sync of deeds, **তল্লাশ, নকল ও এলটি নোটিশ** across computers and the web app (one account)
- Mouza and deed-writer directories are kept current from the server automatically
- All deed records are stored locally, with automatic daily backups, a restore wizard and optional
  Google Drive backup of PDFs
- **Automatic updates:** checked at launch and every six hours, downloaded in the background and
  installed when the application closes

### Mobile Application (Android)

The mobile application operates in conjunction with the desktop software and removes the need
for manual data entry.

- **দলিলসেবা AI document scanning:** capture the National ID cards of the parties and scan the
  QR code of a দাখিলা or নামজারি খতিয়ান
- **Direct transfer to the desktop:** names, addresses, দাগ and খতিয়ান numbers are extracted
  and delivered to the corresponding step of the open deed, where the user reviews them and
  confirms with **যোগ করুন**
- **QR verification of the land record:** for a দাখিলা or নামজারি খতিয়ান, the app checks the matching online
  record and marks each paper as genuine, fake or unverifiable
- **Document verification:** QR-based checks for 10 document types, including দাখিলা, খতিয়ান ও নামজারি,
  এ-চালান, ই-রিটার্ন, দলিল and জন্ম ও মৃত্যু নিবন্ধন
- **Reference services:** market values, mouza directory, 359 land classes, laws and regulations,
  sample forms, a 700+ page registration manual, দলিল পেডিয়া and the office directory
- Sign-in with mobile number and OTP; automatic updates verified by SHA-256

See the [mobile app page](https://dolil.github.io/dolilsheba-releases/mobile-app/) for full details.

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
2. Run the installer. The installer is not yet code-signed, so if Windows displays
   **"Windows protected your PC"**, select **More info → Run anyway**.
3. Approve the administrator prompt; the installation folder may be changed if required.
4. Launch the software from the **"দলিল সেবা"** desktop shortcut and sign in. New users register
   with a mobile number verified by OTP.

### Android

1. On the mobile device, download the
   [Android application](https://github.com/dolil/dolilsheba-mobile-releases/releases/latest/download/dolilsheba.apk).
2. Open the downloaded file. On first installation, Android requests permission to
   **install from this source**; grant the permission and select **Install**.
3. The application installs as **"দলিল সেবা"**. Sign in with a mobile number and OTP, open
   **দলিলসেবা AI** from the menu, and scan the QR code shown in the **মোবাইল স্ক্যান** section of
   the deed on the desktop.

## System Requirements

| | Desktop Software | Mobile Application |
|---|---|---|
| Operating system | Windows 10 or 11, 64-bit | Android 7.0 or later |
| Storage | Approximately 200 MB | Approximately 90 MB (download) |
| Internet | Registration, credit purchase, AI scanning, synchronisation and updates | Sign-in, AI scanning, verification and most reference services |

## Updates

Both components check for new versions automatically.

- **Desktop software:** checks at launch and every six hours, downloads in the background and
  installs on exit. Updates may also be checked manually via **আপডেট ও সিঙ্ক → সিস্টেম আপডেট**.
- **Mobile application:** shows "নতুন আপডেট পাওয়া গেছে" when a new version is available and installs
  it after verifying its SHA-256. Updates may also be checked via **আপডেট খুঁজুন** in the menu.

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
  Developed and maintained by <strong>Dolil Sheba</strong>, Sylhet, Bangladesh.<br>
  <sub>© 2024–2026 Dolil Sheba. All rights reserved.<br>
  Dolil Sheba is a private service and is not affiliated with the Government of Bangladesh or any of its agencies.</sub>
</p>
