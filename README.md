# ThinkPad X230 Hackintosh (macOS Big Sur 11.7.10)

![macOS](https://img.shields.io/badge/macOS-Big%20Sur%2011.7.10-orange?style=for-the-badge&logo=apple) ![OpenCore](https://img.shields.io/badge/OpenCore-1.0.5-blue?style=for-the-badge) 

A complete guide to installing and running macOS Big Sur 11.7.10 on the Lenovo ThinkPad X230 with Intel Core i5-3320M. This repository provides a stable OpenCore configuration specifically tested for this setup.

**SPECIAL NOTE: Bluetooth, Audio, and Sleep are currently NOT working**

**CURRENT STATUS: WIP**


## ✅ What's Working / What's Not

This status is for **macOS Big Sur 11.7.10** with **OpenCore 1.0.5** on **Intel i5-3320M**.

### ✅ Fully Functional

* **CPU Power Management** (i5-3320M)
* **GPU (Intel HD 4000)** 
* **Ethernet** 
* **WIFI** 
* **USB 2.0 & 3.0** (all ports mapped correctly)
* **TrackPad** with basic gestures
* **Keyboard** (most function keys working, install YogaSMC app)
* **Battery Status**
* **SD Card Reader**
* **iMessage, FaceTime, App Store** (with valid SMBIOS)

### ❓ Not tested

* **DisplayPort Video Output**

### ❌ Not Working / Issues

* **Trackpoint** - buggy when scrolling
* **Bluetooth** - Completely non-functional, needs fixing
* **Audio** - No sound output/input
* **Sleep/Wake** - Dosen't go to sleep
* **VGA Port** - Unsupported
* **Fingerprint Reader** - Unsupported
* **WWAN/4G Card** - Unsupported

