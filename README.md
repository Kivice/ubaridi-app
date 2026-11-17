<div align="center">

<img src="assets/ubaridi_helmet_icon.png" width="96" alt="Ubaridi Helmet Logo" />

# Ubaridi — Ride, Deliver & Order Across Kirinyaga

**Fast local boda-boda rides, parcel deliveries, and campus/town errands built for Kirinyaga University (KyU), Kutus, Kerugoya, Kagio & Sagana.**

![Beta Release](https://img.shields.io/badge/release-v1.0.0--beta.1-00C853?style=for-the-badge)
![Platform](https://img.shields.io/badge/Android-APK%20Release-111C18?style=for-the-badge&logo=android&logoColor=00C853)
![Light Build](https://img.shields.io/badge/APK%20Size-18%E2%80%9320.4%20MB-00C853?style=for-the-badge)

</div>

---

## Download the Android Beta

Pick the build that matches your phone (most phones made in the last 7+ years use **64-bit ARM64**):

| Device Type | File | Size | Download |
|---|---|---|---|
| **Most Modern Android Phones** *(Recommended — 64-bit `arm64-v8a`)* | `app-arm64-v8a-release.apk` | **20.42 MB** | [**Direct Download**](https://github.com/Kivice/ubaridi-app/releases/latest/download/app-arm64-v8a-release.apk) · [`repo file`](apks/app-arm64-v8a-release.apk) |
| **Older / Entry-Level Phones** *(32-bit `armeabi-v7a`)* | `app-armeabi-v7a-release.apk` | **18.02 MB** | [**Direct Download**](https://github.com/Kivice/ubaridi-app/releases/latest/download/app-armeabi-v7a-release.apk) · [`repo file`](apks/app-armeabi-v7a-release.apk) |

> [!TIP]
> Not sure which file to pick? Download **`app-arm64-v8a-release.apk` (20.42 MB)** first. If Android says the package isn't compatible with your CPU, install **`app-armeabi-v7a-release.apk` (18.02 MB)** instead.

> [!NOTE]
> **Sign-in tip for this beta:** Please create an account or sign in using **Email & Password** while Google Sign-In for the release signature finishes rollout.

---

## Install in 30 Seconds

1. Tap **Direct Download** above on your Android phone.
2. Open the downloaded `.apk` from your browser downloads or Files app.
3. If Android asks, tap **Settings -> Allow from this source** (needed once for beta builds outside Play Store).
4. Tap **Install**, open **Ubaridi**, and try booking a ride, parcel drop, or town errand around Kutus & KyU!

---

## What You Can Test Right Now

- **3 Local Services in One App:**
  - **Boda Ride** (`KES 50` base) — quick campus & town hops.
  - **Parcel Delivery** (`KES 70` base) — send packages safely with rider tracking.
  - **Town / Campus Order** (`KES 100` base) — pick up shop items, printing, gas, or food from spots around Kutus & KyU.
- **Kirinyaga-First Interactive Map:** Switch between **Street** and **Satellite** maps, use high-accuracy GPS pinpoint or drag-to-pin crosshair, tap KyU/Kutus landmark stages (Kilele Tuition Block, Mjini Market, Spenza/Kagio, Joy Millers), and bookmark frequent hostels or stages.
- **Safaricom M-Pesa & Trip Safety:** STK Push checkout dialog, 4-digit Trip PIN confirmation, downloadable/copyable digital receipt codes, and emergency SOS alert access.
- **Snappy Performance + Calm Light & Dark Modes:** Built with Flutter's native **Impeller Vulkan** pipeline, trimmed map memory caches, and compressed assets so even midrange phones stay smooth at ~20 MB.

---

## Send Beta Feedback

We'd love honest feedback on what feels great and what needs polish:
- Map panning smoothness on your phone & Street vs. Satellite readability
- GPS pinpoint & hostel/stage pickup accuracy around KyU, Kutus, Kerugoya & Sagana
- Dark mode vs. Light mode contrast and button spacing
- Any bugs during signup, booking, or M-Pesa checkout

**How to reach us:**
- Inside the app: open the **Menu drawer -> Share Beta Feedback**
- Email: **info@kiviceubaridiapp.tech**
- GitHub: [Open an Issue](https://github.com/Kivice/ubaridi-app/issues/new)

---

<details>
<summary><strong>APK Integrity Verification (SHA-256 Checksums)</strong></summary>

Checksums are also stored in [`SHA256SUMS.txt`](SHA256SUMS.txt):

```text
73927904784567723cb8dbb9b6e00941c0aa4a9f5c1f403d8dd67f17b3dbdc2c  apks/app-arm64-v8a-release.apk
73c36f4964711813cf5916c8249f074ec9b5278e8f6bace68c67a692e9e27f0f  apks/app-armeabi-v7a-release.apk
```

</details>
