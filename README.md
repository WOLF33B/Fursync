that great but i changing to it. please read it to make sure it correct
# FurSync (RIOT FurSync)

> **Companion App for the Fursync Ecosystem**

[![Platform](https://img.shields.io/badge/Platform-Android-green.svg)](https://developer.android.com/)
[![Target SDK](https://img.shields.io/badge/Target--SDK-34-blue.svg)](https://developer.android.com/)


---

## About FurSync

**FurSync** is the official companion mobile application for compatible **RIOT** firmware and hardware devices. Designed with a **privacy-first** architecture, FurSync establishes a secure bridge between your Android device and Fursync devices or RIOT compatible hardware,
> ⚠️ **Note**: FurSync are closed ecosystem and requires a compatible physical Fursync device or Riot compatible devices (sold separately).
---

##  Key Features

###  Real-Time Monitoring and Analytics 
* **Live data**         : Track Humidity, Temperature, CPU Statistic, system uptime, signal strength, and more.
* **Visual Analytics**  : Interactive usage graphs tracking session duration, power levels, and performance trends.
* **Session Tracking**  : Automatically records session metrics (up to the last 30 sessions).
* **Self-Diagnosis**    : Built-in support for fault detection.
* ...and more.

### Smart Feature
* **Overheat Protection** : Prevents hardware damage by automatically managing high-temperature thresholds.
* **Sweating Prevention** : Intelligent protection profiles to minimize moisture and heat buildup during extended use.
* **Boot Persistence**    : Save custom configurations and automatically restore preferences at startup.
* **Auto save**         : Automatically saved lasted configuration that will be loaded at boot
* **Notifications Relay** : Relay incoming phone calls, message and app notifications to the hardware with it own category.
* ...and more.
  
### Security and Encryption
* **Bluetooth® LE secure connections** : A Front Layer security keeping passive sniffers out.
* **3Digit Hand Shake Core 2.0**: Custom handshake protocol designed to punish anomalies and slow down online brute-force attack
* **3DHS-EN 2.0**: End-to-end multi layer encrypted protocol securing all communication between your mobile app and the hardware.
* **3DHS-ENEX (Extended Protocol)**: Advanced Layer 0 security features on supported hardware, allowing fully encrypted payloads to be wrapped seamlessly with secondary encryption (from ChaCha20 up to AES-256).

### Modern Personalization
* **Material 3 & Monet Engine**: Supports Android 12+ dynamic color themes matching your wallpaper.
* **AMOLED Dark Mode**: True black and White themes for display clarity under sunlight and battery saving.
* **Multiple Themes**: Came with many themes, and more are coming 

---

## Hardware Requirements
FurSync minimum requirement to work (Some protection features may be disabled on legacy hardware):
* **Android**: 9
* **Bluetooth**: 5.0
* **Bluetooth protocol**: BLE, offloaded filtering, offloaded scan batching, multiple advertisements, High Speed (2M PHY), maximum advertising data length 31 or more bytes.
* **Ram** : 4gb ram (at least 300mb free)
* **SOC** : Snapdragon 825 or equivalent

FurSync Recommended requirement:
* **Android**: 14 - 16
* **Bluetooth**: 5.1 or newer
* **Bluetooth protocol**: All minimum features plus periodic advertising, extended advertising, and maximum advertising data length 512 or more bytes.
* **Ram** : 8gb ram (atleast 400mb free)
* **SOC** : Snapdragon 865 or better



---

## Getting Started

1. **Install**: Download the latest FurSync APK and install it on your Android smartphone.
 > ⚠️ **Note**: Android enforces restrictions and 24 hours warning delays on sideloaded apps. To skip or resolve this, please refer to our wiki for details on sideloading procedures.
2. **Setup**: Launch the app and complete the initial permission setup guide.
3. **Power On Hardware**: Turn on your Fursync device and wait few second until it is in pairing mode (LED indicator blinking).
> ⚠️ **Note**: If the LED indicator is disabled in settings, the device will not blink when in pairing mode.
4. **Pair Device**: Tap **Register New Devices** from the sidebar menu to scan and pair your hardware.
> ⚠️ **Note**: If a user password has been set on the device, you must pair using the user password instead of the master password. If the password is changed from another device, re-pairing is required. We recommend not removing/forgetting the device from the app before re-pairing to preserve historical device data.
---

## Privacy And Data Policy

* **100% Local Data**: All device settings, nicknames, bio, and usage history remain strictly stored on your phone.
* **Internet usage** : The app only use internet at boot to check update, the app only contact one way communication to publicly available server such as github without reporting anything else
* **Zero Telemetry**: We do not collect, track, store, or sell any personal data, analytics, or location details.
* **Zero Ads & Zero In-App Purchases**: FurSync is free software provided for the fursync ecosystem.

---

## Developer & Credits

made with loved by **WOLF33B**.

* **XDA Forums**: [wolf33b](https://xdaforums.com/m/wolf33b.10009191/)
* **GitHub**: [@wolf33b](https://github.com/wolf33b)
* **Instagram**: [@WOLF33B](https://instagram.com/WOLF33B)

---
