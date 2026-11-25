<div align="center">

<img src="assets/ubaridi_helmet_icon.png" width="96" alt="Ubaridi Helmet Logo" />

# Ubaridi — Ride, Deliver & Order Across Kirinyaga

**Fast local boda-boda rides, parcel deliveries, and campus/town errands built for Kirinyaga University (KyU), Kutus, Kerugoya, Kagio & Sagana.**

![Beta Release](https://img.shields.io/badge/release-v1.0.0--beta.3-00C853?style=for-the-badge)
![Platform](https://img.shields.io/badge/Android-APK%20Release-111C18?style=for-the-badge&logo=android&logoColor=00C853)
![Light Build](https://img.shields.io/badge/APK%20Size-18.1%E2%80%9320.4%20MB-00C853?style=for-the-badge)

</div>

---

## Download the Android Beta

Pick the build that matches your phone (most phones made in the last 7+ years use **64-bit ARM64**):

| Device Type | File | Size | Download |
|---|---|---|---|
| **Most Modern Android Phones** *(Recommended — 64-bit `arm64-v8a`)* | `app-arm64-v8a-release.apk` | **20.43 MB** | [**Direct Download**](https://github.com/Kivice/ubaridi-app/releases/latest/download/app-arm64-v8a-release.apk) · [`repo file`](apks/app-arm64-v8a-release.apk) |
| **Older / Entry-Level Phones** *(32-bit `armeabi-v7a`)* | `app-armeabi-v7a-release.apk` | **18.07 MB** | [**Direct Download**](https://github.com/Kivice/ubaridi-app/releases/latest/download/app-armeabi-v7a-release.apk) · [`repo file`](apks/app-armeabi-v7a-release.apk) |

> [!TIP]
> Not sure which file to pick? Download **`app-arm64-v8a-release.apk` (20.43 MB)** first. If Android says the package isn't compatible with your CPU, install **`app-armeabi-v7a-release.apk` (18.07 MB)** instead.

> [!NOTE]
> **Sign-in tip for this beta:** Please create an account or sign in using **Email & Password** while Google Sign-In for the release signature finishes rollout.

> [!CAUTION]
> **BETA PAYMENT WARNING — DO NOT ENTER YOUR M-PESA PIN:** If an M-Pesa STK Push prompt pops up on your phone while testing checkout, **cancel or dismiss it — DO NOT enter your M-Pesa PIN or your money goes to the void!** Use this beta purely to preview the checkout UI and countdown flow.

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
- **Kirinyaga-First Interactive Map & Real Road Routing:** Switch between **Street** and **Satellite** maps, preview live **OSRM road polylines** before booking, use high-accuracy GPS pinpoint or drag-to-pin crosshair, tap KyU/Kutus landmark stages (Kilele Tuition Block, Mjini Market, Spenza/Kagio, Joy Millers), and bookmark frequent hostels or stages.
- **Live Trip Sharing, SSE Updates & SOS Safety:** Sub-second **SSE live trip tracking**, one-tap **Share Live Trip** links for WhatsApp/SMS, STK Push checkout dialog *(preview only — do **not** enter your real M-Pesa PIN)*, 4-digit Trip PIN confirmation, copyable digital receipt preview, and emergency **SOS + WhatsApp/SMS** alert access.
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
2be980fe3434c9cec56e5b0021cee1bc72f269fee8b79f09ac9e8f9a933dda46  apks/app-arm64-v8a-release.apk
59974d16fee1d676a1ac20399c15a86f626b9a14ed5a09ecd47431c4a730104c  apks/app-armeabi-v7a-release.apk
```

</details>
