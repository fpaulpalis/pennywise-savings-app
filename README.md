<p align="center">
<a href=""><img width="200" height="200" src="https://github.com/fpaulpalis/PennyWise-GreenStash/blob/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.webp"></a>
</p>

<h1 align="center">PennyWise Savings App</h1>

<p align="center">
<img src="https://img.shields.io/badge/status-archived-lightgrey?style=for-the-badge" alt="archived">
<img src="https://img.shields.io/badge/course-ITE%20393%20Application%20Development-blue?style=for-the-badge" alt="course">
<img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="license">
</p>

> **⚠️ ARCHIVED - NO LONGER MAINTAINED**
> This repository is archived and no longer maintained. This was created as a school activity / Performance Task (PeTa) for **BSCS 2-2S: ITE 393 - Application Development**. No further updates, bug fixes, or support will be provided.

**PennyWise Savings App** is a fork of *[GreenStash](https://github.com/Pool-Of-Tears/GreenStash)*, a FOSS Android app by *[Pool-Of-Tears](https://github.com/Pool-Of-Tears)*. It helps users manage savings goals while maintaining GreenStash's core functionality with project-specific modifications.

---

<h2 align="center">Screenshots</h2>

<p align="center">
<img src="https://github.com/user-attachments/assets/abfc2f9c-bbe6-47cc-b172-f22ae73d28ae" width="250" alt="screenshot 1">
<img src="https://github.com/user-attachments/assets/e51303eb-dbb4-476b-8c58-cb5c6ba43663" width="250" alt="screenshot 2">
<img src="https://github.com/user-attachments/assets/0f46e1f2-60af-48ce-9501-73ee2cf51056" width="250" alt="screenshot 3">
</p>
<p align="center">
<img src="https://github.com/user-attachments/assets/b7d86f8b-1861-4ee0-8c85-0382e4b806a0" width="250" alt="screenshot 4">
<img src="https://github.com/user-attachments/assets/6d18e19e-f5fa-49e4-bc55-24d5ffa944f7" width="250" alt="screenshot 5">
<img src="https://github.com/user-attachments/assets/74037d17-0191-404b-b413-f68fbcaec667" width="250" alt="screenshot 6">
</p>

---

## What the project does

PennyWise is an offline-first Android savings goal tracker built with Modern Android Development (MAD).

- Create and manage multiple savings goals with target amount and deadline
- Track deposits and withdrawals with detailed transaction history
- Automatically calculates how much you need to save **daily / weekly / monthly** to achieve your goal before deadline
- Visual progress tracking
- **Fully offline** — does not require internet permission; all data stored locally using Room DB
- Clean & beautiful UI based on Google's Material Design 3 with [Material You](https://m3.material.io/) dynamic theming on Android 12+
- Single activity architecture, no fragments, only composable destinations - UI and logic written in pure Kotlin
- Compatible with Android 7.0 and above (API 24+)

## Why the project is useful

- **For users:** Helps develop financial discipline by breaking large savings goals into small, manageable contributions.
- **For privacy:** Since it's fully offline, financial data never leaves the device.
- **For students:** Serves as a practical example of Android App Development using Kotlin, Jetpack Compose, Room, Coroutines, Flow, Hilt, Lottie, and Coil.
- **For low-end devices:** No login, no internet, lightweight and accessible.

## How users can get started with the project

> Note: As this is an archived academic project, use it for learning/demo purposes.

**Prerequisites:**
- Android Studio Hedgehog or newer
- JDK 17
- Android SDK with API 24+

**1. Clone the repository**
```bash
git clone https://github.com/fpaulpalis/pennywise-savings-app.git
cd pennywise-savings-app
```

**2. Build & Run**
1. Open the folder in Android Studio: `File > Open`
2. Wait for Gradle Sync to complete
3. Run on emulator or physical device: `Run > Run 'app'`

No API keys, Firebase, or internet setup is required.

**Optional: Install APK**
If a release APK is available in Releases, download it and enable "Install from unknown sources" on your Android device.

## Where users can get help with your project

This project is **archived**, so active support is not available.

- For original app issues and documentation, please refer to upstream: [Pool-Of-Tears/GreenStash](https://github.com/Pool-Of-Tears/GreenStash)
- For Android development help: [Android Developers Docs](https://developer.android.com/) and [Jetpack Compose Docs](https://developer.android.com/jetpack/compose)
- You can open an Issue in this repo for historical reference, but a response is not guaranteed.

## Who maintains and contributes to the project

**Maintenance Status:** Archived - No active maintainer.

This was created for **ITE 393 - Application Development P3 PeTa** by:

1. Alos, Mark Vincent
2. Danao, Jilbert
3. Neri, Mikael Vladimir
4. Palis, Francis Paul - [fpaulpalis](https://github.com/fpaulpalis)

**Original Credits:**
- Core app: [GreenStash](https://github.com/Pool-Of-Tears/GreenStash) by [Stɑrry Shivɑm](https://github.com/starry-shivam) and [Pool-Of-Tears](https://github.com/Pool-Of-Tears) contributors
- This fork contains project-specific modifications for academic purposes.

---

### Tech Stack

- [Kotlin](https://kotlinlang.org/) - Official Android language
- [Coroutines](https://kotlinlang.org/docs/coroutines-overview.html) - Async I/O
- [Flow](https://kotlinlang.org/api/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/-flow/) - Cold async data stream
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Robust & maintainable design
- [Jetpack Compose](https://developer.android.com/jetpack/compose) - Modern toolkit for native UI
- [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) - Observable data
- [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - UI-related data holder
- [Lottie](https://airbnb.design/lottie) - Real-time After Effects animations
- [Coil](https://coil-kt.github.io/coil/compose) - Image loading
- [Kotlinx.serialization](https://kotlinlang.org/docs/serialization.html) - Serialization
- [Dagger-Hilt](https://dagger.dev/hilt) - Dependency Injection
- [Room database](https://developer.android.com/jetpack/androidx/releases/room) - Local persistence over SQLite

### License

[MIT License](https://github.com/fpaulpalis/PennyWise-GreenStash/blob/main/LICENSE) © [Stɑrry Shivɑm](https://github.com/starry-shivam)
