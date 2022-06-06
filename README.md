# Lenovo ThinkPad T480s - OpenCore Configuation

<img align="right" src="/Images/t480s-monterey.png" alt="macOS Monterey running on the T440p" width="425">

[![macOS](https://img.shields.io/badge/macOS-Monterey-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![macOS](https://img.shields.io/badge/macOS-Mammoth-brightgreen.svg)](https://developer.apple.com/documentation/macos-release-notes)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.8.0-blue)](https://github.com/acidanthera/OpenCorePkg)
[![License](https://img.shields.io/badge/license-MIT-purple)](/LICENSE)


**DISCLAIMER:**  
This is just my own ThinkPad T480s OpenCore EFI
I am not responsible for any damages you may cause.  
Should you find an error or improve anything — whether in the config or in the documentation — please consider opening an issue or pull request.

> The EFI base are from [Valnoxy T480 OpenCore](https://github.com/valnoxy/t480-oc).


&nbsp;

## 💻 My Hardware

| Category  | Component                                  |
| --------- | ------------------------------------------ |
| CPU       | Intel(R) Core(TM) i5-8350U CPU @ 1.70GHz   |
| GPU       | Intel UHD Graphics 620                     |
| SSD       | Intel SSDPEKKF512G8L M.2 NVMe SSD          |
| Memory    | 20GB DDR4 2400Mhz                          |
| Camera    | 720p Camera                                |
| WiFi & BT | Intel Dual Band Wireless AC 8265           |
| Display   | 14" Full HD (1920x1080) IPS, non-touch     |

&nbsp;

## 🔄 Update Tracker

| Software  | Version                                                       |
| --------- | --------------------------------------------------------------|
| [MacOS](https://www.apple.com/macos/)                            | 12.4   |
| [OpenCore](https://github.com/acidanthera/OpenCorePkg/releases)  | 0.6.6  |

&nbsp;

## Status

<details>  
<summary><strong>✅ What's working</strong></summary>
</br>
 
- [X] Intel WiFi & Bluetooth (thanks to [itlwn](https://github.com/OpenIntelWireless/itlwm))
- [X] Brightness / Volume Control
- [X] Battery Information
- [X] Audio (Audio Jack & Speaker)
- [X] USB Ports & Built-in Camera
- [X] Graphics Acceleration
- [X] Trackpoint / Touchpad
- [X] Power management / Sleep
- [X] FaceTime / iMessage (iServices)
- [X] HDMI
- [X] Automatic OS updates
- [X] Handoff / Universal Clipboard
- [X] SIP / FireVault 2
- [X] USB-C

</details>

<details>  
<summary><strong>⚠️ What's not working</strong></summary>
</br>

- [ ] Safari DRM ```Use Chromium powered Browser or Firefox to watch Amazon Prime Video, Netflix, Disney+ and others```
- [ ] AirDrop & Continuity
- [ ] Fingerprint Reader (Disabled with NoTouchID kext)
- [ ] Thunderbolt 3

</details>

<details>  
<summary><strong>🔄 Not tested</strong></summary>
</br>

- [ ] Sidecar Wireless
- [ ] Apple Watch Unlock
- [ ] WWAN
- [ ] Dualbooting Windows / Linux (with OpenCore)
- [ ] Sidecar (Cable) / AirPlay to Mac


</details>

&nbsp;

## ⭐️ Feedback
Did you find any bugs or just have some questions? Feel free to provide your feedback using the Discussions tab.

&nbsp;

## 📜 License

This repo is licensed under the [MIT License](https://github.com/valnoxy/t480-oc/blob/main/LICENSE).

OpenCore is licensed under the [BSD 3-Clause License](https://github.com/acidanthera/OpenCorePkg/blob/master/LICENSE.txt).

---
```Copyright (c) 2022 Wakhid Nusa. <ask@wakhid.com>```