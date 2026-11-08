<p align="center">
  <img src="icon.png" alt="Dolilsheba" width="112" height="112">
</p>

<h1 align="center">Dolilsheba · দলিল সেবা</h1>

<p align="center">
  <strong>Smart Deed Management System (SDMS)</strong><br>
  Desktop software for writing Bengali land deeds, with a companion Android app that scans
  NID cards and land records straight into the deed.
</p>

<p align="center">
  <a href="https://github.com/dolil/dolilsheba-releases/releases/latest"><img src="https://img.shields.io/github/v/release/dolil/dolilsheba-releases?label=Windows&color=16a34a&style=for-the-badge&logo=windows&logoColor=white" alt="Latest Windows release"></a>
  <a href="https://github.com/dolil/dolilsheba-mobile-releases/releases/latest"><img src="https://img.shields.io/github/v/release/dolil/dolilsheba-mobile-releases?label=Android&color=16a34a&style=for-the-badge&logo=android&logoColor=white" alt="Latest Android release"></a>
  <a href="https://github.com/dolil/dolilsheba-releases/releases"><img src="https://img.shields.io/github/downloads/dolil/dolilsheba-releases/total?label=Downloads&color=15803d&style=for-the-badge" alt="Total downloads"></a>
</p>

<p align="center">
  <a href="https://dolil.github.io/dolilsheba-releases/"><strong>⬇️ Download page</strong></a>
  &nbsp;·&nbsp;
  <a href="https://dolilsheba.com">Website</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/dolil/dolilsheba-releases/releases">All versions</a>
</p>

---

## Download

| | Platform | Get it |
|---|---|---|
| 🖥️ **Desktop software** | Windows 10 / 11 (64-bit) | [**Download installer (.exe)**](https://dolil.github.io/dolilsheba-releases/) |
| 📱 **Mobile app** | Android 7.0 or newer | [**Download APK**](https://github.com/dolil/dolilsheba-mobile-releases/releases/latest/download/dolilsheba.apk) |

The [download page](https://dolil.github.io/dolilsheba-releases/) always points at the newest
version of both, with release notes.

## What's included

### 🖥️ Desktop software (Windows)

The main workspace for deed writers, lawyers, real estate companies and banks.

- **32 types** of Bengali land deed documents, with ready templates for common property deeds
- Print-ready output with proper legal formatting
- **Works offline**: write and print deeds without internet; it's only needed for license and sync
- **নকল, তল্লাশ ও এলটি নোটিশ** sync between your computer and the website
- Mouza and deed-writer lists stay current from the server automatically
- Your deeds are stored locally on your computer
- **Updates itself**: new versions download and install in one click

### 📱 Mobile app (Android)

The phone app pairs with the desktop software, so you don't have to type details in by hand.

- **দলিলসেবা AI scanning**: photograph the parties' NID cards and scan the QR code on a
  দাখিলা or নামজারি খতিয়ান
- **Sends to your computer**: names, addresses, দাগ and খতিয়ান numbers land in the right
  step of the open deed on the desktop. You review them and click **যোগ করুন**
- **Information services** on the go: market values, mouza lists, laws and rules,
  sample forms, office directory and document verification
- Updates itself from this project's releases

**How they work together**

```
 ① Phone            ② Phone              ③ Phone → Computer        ④ Computer
 Scan the QR   →    Scan NID and    →    AI reads the details  →   Check, click
 on the deed        দাখিলা / খতিয়ান       and sends them             "যোগ করুন" — done
 ("মোবাইল স্ক্যান")
```

## Installation

### Windows

1. Open the [download page](https://dolil.github.io/dolilsheba-releases/) and click
   **Windows এর জন্য ডাউনলোড**. You'll get a file named `dolilsheba-Setup-x.y.z.exe`.
2. Run the installer and follow the steps.
3. If Windows shows **"Windows protected your PC"**, click **More info → Run anyway**.
4. Start **Dolilsheba** from the desktop shortcut and sign in.

### Android

1. On your phone, download the
   [APK](https://github.com/dolil/dolilsheba-mobile-releases/releases/latest/download/dolilsheba.apk).
2. Open it. The first time, Android asks you to **allow installs from this source**.
   Allow it, then go back and tap **Install**.
3. Open **দলিল সেবা**, sign in, and scan the QR code shown in the desktop's
   **মোবাইল স্ক্যান** section to connect the phone to a deed.

## System requirements

| | Desktop | Mobile |
|---|---|---|
| OS | Windows 10 or 11, 64-bit | Android 7.0+ |
| Storage | ~200 MB | ~90 MB download |
| Internet | For sign-in, license, sync and updates | For scanning and sending to the desktop |

## Updates

Both apps check for new versions on their own.

- **Desktop**: an update notice appears inside the app. You can also check from
  **Help → Check for Updates**.
- **Mobile**: the app tells you when a new version is ready and installs it from here.

Release notes for every version are on the [Releases](https://github.com/dolil/dolilsheba-releases/releases)
page (desktop) and the [mobile releases](https://github.com/dolil/dolilsheba-mobile-releases/releases)
page (Android).

## Verifying downloads

Every Android release lists the APK's **SHA-256** in its notes and on the download page.
All APKs are signed with the same key, with certificate SHA-256:

```
d368f1219204e7beb6589b12455c66347516b64736ed0763ec6e0e6b6560ac83
```

Only download installers from this repository, the
[mobile releases](https://github.com/dolil/dolilsheba-mobile-releases) repository, or
[dolilsheba.com](https://dolilsheba.com).

## Support

- 🌐 Website: [dolilsheba.com](https://dolilsheba.com)
- 📧 Email: [dolilsheba@gmail.com](mailto:dolilsheba@gmail.com) · [info@dolilsheba.com](mailto:info@dolilsheba.com)

## About this repository

This repository holds **release files only**. No source code is hosted here.
Releases are built and published by CI.

<details>
<summary>How the download page stays current</summary>

`index.html` is served by GitHub Pages at <https://dolil.github.io/dolilsheba-releases/>.
It reads two generated files. Don't edit them by hand:

- `latest.json`: the newest published desktop release of this repository
- `mobile.json`: a copy of `latest.json` from the newest release of
  [`dolil/dolilsheba-mobile-releases`](https://github.com/dolil/dolilsheba-mobile-releases)

[`.github/workflows/update-latest.yml`](.github/workflows/update-latest.yml) rewrites both on
every release event here and hourly, which is how it picks up Android releases. The page only
falls back to the GitHub API if `latest.json` is missing, because anonymous API callers share
a limit of 60 requests an hour per IP address.

</details>

---

<p align="center">
  Developed and maintained by <strong>Upakul Dolil Sheba</strong>, Sylhet, Bangladesh.<br>
  <sub>© 2024–2026 Upakul Dolil Sheba. All rights reserved.</sub>
</p>
