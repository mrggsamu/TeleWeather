# TeleWeather — APK Only

This repository hosts the **Android APK builds** of **TeleWeather** — a prototype app that simulates early disaster detection from satellite-like scenarios. It estimates risk for **Flood**, **Wildfire**, **Cyclone**, **Drought**, and **Landslide**, and lets you save **alerts**. Optionally, it can ingest local sensor data over classic **Bluetooth** (HC-05/ESP32).

> ⚠️ **Demo notice:** The “AI” logic is **simulated** for prototyping. Bluetooth is optional.

---

## Download

- Go to the **[Releases](../../releases)** page and grab the latest `TeleWeather_vX.Y.Z.apk`.
- Minimum Android: **API 24 (Android 7.0+)**  
- Target Android: **API 34**  
- Processor: universal APK (works on most modern devices).

### Install on device (sideload)

**Option A — on the phone**
1. Copy the `.apk` to your device.
2. Tap it and allow “Install unknown apps” for your file manager/browser when prompted.

**Option B — via ADB**
```bash
adb install -r TeleWeather_vX.Y.Z.apk
