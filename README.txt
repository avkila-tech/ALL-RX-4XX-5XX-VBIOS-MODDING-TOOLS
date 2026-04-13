# AMD Polaris (RX 4XX/5XX) vBIOS Modding Toolkit
### A specialized archive for modifying, flashing, and repairing AMD Polaris-based graphics cards.

---

### Contact & Support
* Maintainer: avkila
* Discord: avkila (Miyconst server)
* Instagram: @avkilasmodding

---

### Overview
This repository contains the essential toolset for vBIOS modification on AMD RX 470/480 and RX 570/580/590 series GPUs. It is specifically designed for timing optimization, undervolting, and restoring functionality to 2048SP variants or legacy mining cards.

### Core Utilities

#### 1. Flashing & Backup
* amdvbflash (ATIFlash): The standard utility for reading (dumping) and writing (flashing) vBIOS images to the SPI flash of the GPU.

#### 2. vBIOS Editing & Optimization
* Red BIOS Editor (RBE): The modern standard for power limit and fan control adjustments. Highly reliable for fine-tuning Polaris and even some newer architecture parameters.
* Polaris BIOS Editor (PBE): The classic "One-Click" solution. Best known for its ability to automatically patch memory timings (straps) for better performance in compute and gaming tasks.
* SRBPolaris: A versatile editor that combines power limit, voltage offset, and timing adjustments in a single interface.

#### 3. Driver & Boot Compatibility
* AMD GOP 1.6x / 1.50 (Signed): Modified Graphics Output Protocol (GOP) drivers. These allow for UEFI boot support on modded vBIOS images.
* Note: Secure Boot MUST be disabled in the motherboard BIOS to avoid a black screen or POST failure with these files.
* atikmdag-patcher: A vital utility that patches official AMD Windows drivers to bypass BIOS signature checks. This prevents "Error Code 43" on modified firmware.

---

### Safety & Disclaimer
### USE AT YOUR OWN RISK.
* Modifying voltages or power limits can lead to permanent hardware failure.
* Always backup your original ROM before flashing.
* Ensure your card has a Dual-BIOS switch or that you have a CH341A programmer ready for recovery.
* I am not responsible for any hardware damage, fried VRMs, or data loss.

---

### Status
* Architecture: Polaris (RX 400 and RX 500 Series)
* Repository Version: 1.1 (Updated April 2026)
