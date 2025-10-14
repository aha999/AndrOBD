<p align="center">
  <img src="fastlane/metadata/android/en-US/images/tvBanner.png" alt="AndrOBD Banner" />
</p>

<h1 align="center">🚗 AndrOBD</h1>
<p align="center">
  Open-source OBD2 diagnostics for Android — connect to your car, read data, analyze, and explore.
</p>

<p align="center">
  <a href="https://github.com/fr3ts0n/AndrOBD/actions"><img src="https://github.com/fr3ts0n/AndrOBD/workflows/Android%20CI/badge.svg" alt="Android CI" /></a>
  <a href="https://github.com/fr3ts0n/AndrOBD/issues"><img src="https://img.shields.io/github/issues/fr3ts0n/AndrOBD?color=red" alt="Issues" /></a>
  <a href="https://liberapay.com/AndrOBD/donate/"><img src="https://img.shields.io/liberapay/receives/AndrOBD?label=Liberapay" alt="Liberapay" /></a>
  <a href="https://www.reddit.com/r/AndrOBD/"><img src="https://img.shields.io/reddit/subreddit-subscribers/AndrOBD?color=orange" alt="Subreddit" /></a>
  <a href="https://t.me/joinchat/G60ltQv5CCEQ94BZ5yWQbg"><img src="https://img.shields.io/badge/chat-on%20Telegram-blue" alt="Telegram" /></a>
  <a href="https://matrix.to/#/#AndrOBD:matrix.org"><img src="https://img.shields.io/badge/chat-on%20Matrix-blue" alt="Matrix" /></a>
  <a href="https://github.com/fr3ts0n/AndrOBD/blob/master/LICENSE"><img src="https://img.shields.io/github/license/fr3ts0n/AndrOBD?color=lightgrey" alt="License" /></a>
</p>

---

## 🧭 Overview

**AndrOBD** allows your Android device to connect to your car’s onboard diagnostics (OBD2) system via any **ELM327-compatible adapter** (Bluetooth, Wi-Fi, or USB).  
It’s completely **free and open-source**, with a built-in **Demo Mode** so you can test it even without a car connection.

🔹 **View real-time data**  
🔹 **Read & clear fault codes**  
🔹 **Analyze & record driving performance**  
🔹 **Customize your dashboards and data items**

---

## 📲 Install

[![Latest Release](https://img.shields.io/github/v/release/fr3ts0n/AndrOBD?label=latest%20version&sort=semver)](https://github.com/fr3ts0n/AndrOBD/releases)
[![F-Droid](https://img.shields.io/f-droid/v/com.fr3ts0n.ecu.gui.androbd)](https://f-droid.org/en/packages/com.fr3ts0n.ecu.gui.androbd/)
[![Telegram Alpha/Beta](https://img.shields.io/badge/alpha/beta-on%20Telegram-blue)](https://t.me/AndrOBD_dev)

<p align="center">
  <a href="https://f-droid.org/packages/com.fr3ts0n.ecu.gui.androbd/">
    <img src="https://f-droid.org/badge/get-it-on.png" height="80" alt="Get it on F-Droid">
  </a>
</p>

---

## ⚙️ Features

### 🔌 Connection Types
- Bluetooth
- USB
- Wi-Fi

### 🧰 Core Functions
- Read & clear fault codes (DTC)
- Read/record live data
- View freeze frame data
- Read vehicle info (VIN, etc.)

<details>
  <summary><b>Show more features</b></summary>

#### 💡 Additional Features
- Day/Night themes
- Custom dashboards & charts
- Head-Up Display (HUD)
- Save & replay recorded sessions
- CSV data export

#### ⚙️ Customization
- Define your own PIDs & data conversions
- Flexible plugin architecture

#### 🧩 Plugin Support
- [MQTT Publisher](https://f-droid.org/en/packages/com.fr3ts0n.androbd.plugin.mqtt/) — send data to MQTT broker  
- [GpsProvider](https://f-droid.org/en/packages/com.fr3ts0n.androbd.plugin.gpsprovider/) — feed GPS data  
- [SensorProvider](https://f-droid.org/en/packages/com.fr3ts0n.androbd.plugin.sensorprovider/) — feed accelerometer data  
- [Plugin Dev Kit](https://github.com/fr3ts0n/AndrOBD-Plugin)

#### 🌐 Translations
Help translate AndrOBD via [Weblate](https://hosted.weblate.org/engage/androbd/):
- [App dialogs](https://hosted.weblate.org/projects/androbd/strings/)
- [OBD data](https://hosted.weblate.org/projects/androbd/obd-data-descriptions/)
- [Fault codes](https://hosted.weblate.org/projects/androbd/fault-codes/)

</details>

---

## 📸 Screenshots

| Functions | Live Data | Dashboard |
|:--:|:--:|:--:|
| ![](/fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_02.png) | ![](/fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_06.png) | ![](/fastlane/metadata/android/en-US/images/phoneScreenshots/Screenshot_09.png) |

More screenshots:  
➡️ [Website](https://fr3ts0n.github.io/AndrOBD/) • [Screenshots folder](https://github.com/fr3ts0n/AndrOBD/tree/master/fastlane/metadata/android/en-US/images/phoneScreenshots)

---

## 💬 Contribute

AndrOBD is community-driven — your help makes it better!

- 🪲 [Report issues](https://github.com/fr3ts0n/AndrOBD/issues)
- 🔧 [Submit Pull Requests](https://docs.github.com/en/pull-requests)
- 🧪 Test alpha/beta builds on [Telegram](https://t.me/AndrOBD_dev)
- 🧩 Develop [plugins](https://github.com/fr3ts0n/AndrOBD-Plugin)
- 🌍 [Translate on Weblate](https://hosted.weblate.org/engage/androbd/)
- 💬 Join us on [Telegram](https://t.me/joinchat/G60ltQv5CCEQ94BZ5yWQbg) or [Matrix](https://matrix.to/#/#AndrOBD:matrix.org)

<details>
  <summary>Translation status</summary>

#### App dialogs  
[![App strings](https://hosted.weblate.org/widgets/androbd/-/strings/multi-auto.svg)](https://hosted.weblate.org/projects/androbd/strings/)

#### OBD data  
[![OBD data descriptions](https://hosted.weblate.org/widgets/androbd/-/obd-data-descriptions/multi-auto.svg)](https://hosted.weblate.org/projects/androbd/obd-data-descriptions/)

#### Fault codes  
[![Fault codes](https://hosted.weblate.org/widgets/androbd/-/fault-codes/multi-auto.svg)](https://hosted.weblate.org/projects/androbd/fault-codes/)
</details>

---

## 🎨 Design Call

⚠️ **Help wanted!**  
We’re looking for contributors to design & implement a **modern GUI**.  
Check out issues [#104](https://github.com/fr3ts0n/AndrOBD/issues/104) and [#126](https://github.com/fr3ts0n/AndrOBD/issues/126).  
Java & Kotlin are both supported. Contributors will be **credited** here!

---

## ☕ Support Development

AndrOBD is maintained by volunteers.  
If you find it useful, please consider a donation — it helps us spend more time improving it ❤️

| Platform | Link | |
|:--|:--|:--|
| **PayPal** | [paypal.me/fr3ts0n](https://www.paypal.me/fr3ts0n) | <img src="/manual/paypal-donate-icon.png" height="25"/> |
| **Liberapay** | [liberapay.com/AndrOBD](https://liberapay.com/AndrOBD/donate/) | <img src="https://liberapay.com/assets/widgets/donate.svg" height="25"/> |
| **Bitcoin** | `19UApzsc5eDJ5VNDNYCA1bpszPnkcpWeFP` | <img src="/manual/bitcoin_qr_code.png" width="80"/> |

---

## 🙌 Credits

<details>
  <summary>View contributors & supporters</summary>

**Graphic design** — [anaufalm](https://github.com/anaufalm)  
**Start page** — [sampoder](https://github.com/sampoder)  
**Community & Readme revamp** — [aha999](https://github.com/aha999)  
**Translations hosting** — [Michal Čihař](https://github.com/nijel)

Special thanks to all our amazing [donors](#support-development) and open-source contributors ❤️  
Together, we’re making car diagnostics accessible to everyone.

</details>

---

<p align="center">
  <b>🚗 AndrOBD — Open Source. Transparent. Powerful.</b><br/>
  <a href="https://fr3ts0n.github.io/AndrOBD/">Website</a> • 
  <a href="https://github.com/fr3ts0n/AndrOBD/wiki">Wiki</a> • 
  <a href="https://f-droid.org/packages/com.fr3ts0n.ecu.gui.androbd/">F-Droid</a>
</p>
