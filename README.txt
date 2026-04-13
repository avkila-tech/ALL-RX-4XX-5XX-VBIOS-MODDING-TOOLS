# 🎮 AMD Polaris (RX 4XX/5XX) vBIOS Modding Toolkit
**A specialized archive for modifying, flashing, and repairing AMD Polaris-based graphics cards.**

---

### 👤 Contact & Support
* **Developer:** avkila
* **Instagram:** [@avkilasmodding](https://www.instagram.com/avkila.tech)
* **Discord:** `avkila` (Miyconst server)

---

## 📖 Overview
This repository contains the essential toolset for vBIOS modification on AMD RX 470/480 and RX 570/580/590 series GPUs. It is specifically useful for **timing optimization**, **undervolting**, and restoring functionality to **2048SP** variants or ex-mining cards.

### 🛠️ Core Utilities

#### **Flashing & Backup**
* **amdvbflash (ATIFlash):** The standard utility for reading (dumping) and writing (flashing) vBIOS images to the SPI flash of the GPU.

#### **vBIOS Editing**
* **SRBPolaris:** A user-friendly editor for Polaris BIOS files. Supports one-click timing patches, power limit adjustments, and voltage offset modifications.

#### **Driver & Boot Compatibility**
* **AMD GOP 1.6x / 1.50 (Signed):** Modified Graphics Output Protocol (GOP) drivers. These allow for UEFI boot support on modded vBIOS images.
  * *⚠️ Note: Secure Boot MUST be disabled in the motherboard BIOS to avoid a black screen/POST failure with these files.*
* **atikmdag-patcher:** A vital utility that patches the official AMD Windows drivers to bypass BIOS signature checks (prevents **Error Code 43** on modified firmware).

---

## ⚠️ Safety & Disclaimer
**vBIOS MODDING IS EXTREMELY RISKY.**
* Modifying voltages or power limits can lead to permanent hardware failure or fire.
* **Always** backup your original ROM before flashing. 
* Ensure your card has a **Dual-BIOS switch** or that you have a **CH341A programmer** ready for recovery before proceeding.
* I am not responsible for any hardware damage or data loss.

---

## 🗓️ Status
* **Version:** v1.0 (Public Release)
* **Compatibility:** RX 460/470/480 & RX 560/570/580/590 (Polaris architecture).
