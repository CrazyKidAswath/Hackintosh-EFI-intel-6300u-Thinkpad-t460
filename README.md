# 🍏 Hackintosh EFI for Lenovo ThinkPad T460 – macOS Ventura

This is a fully working and tested OpenCore EFI folder for the **Lenovo ThinkPad T460**, configured to run **macOS Ventura** smoothly.

---

## 🖥️ System Specs

- **Model**: Lenovo ThinkPad T460  
- **CPU**: Intel Core i5-6300U  
- **GPU**: Intel HD Graphics 520  
- **RAM**: (User-dependent)  
- **macOS Version**: Ventura (Recommended: 13.0+)

---

## ✅ What's Working

- [x] Intel HD 520 graphics acceleration (QE/CI)
- [x] Audio (AppleALC)
- [x] Trackpad and keyboard with gestures (VoodooPS2)
- [x] Wi-Fi (Intel WiFi with OpenIntelWireless)
- [x] Bluetooth (IntelBluetoothFirmware)
- [x] Webcam
- [x] iCloud, App Store, iMessage, Siri, FaceTime
- [x] Sleep/Wake
- [x] USB ports (mapped)
- [x] Chrome, WhatsApp, and other apps

---

## ⚙️ Tools & Kexts Used

- OpenCore (latest tested version)
- Lilu + WhateverGreen
- AppleALC
- IntelBluetoothFirmware + IntelWiFi
- VirtualSMC + SMCBatteryManager
- USBMap
- VoodooPS2Controller

---

## 🔧 Notes

- BIOS configured for macOS (CFG Lock disabled, VT-d off, etc.)
- SIP is **disabled** for patching (can be re-enabled)
- You may need to generate your own **serial number** via [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

---

## 📂 Installation Tip

Use **macOS Ventura** installer and replace the EFI in your USB with this one. After boot and install, copy EFI to your system’s EFI partition.

---

## ⚠️ Disclaimer

This EFI is provided for educational purposes. Please use at your own risk. Always back up your data.

---

## 🙌 Credits

Thanks to the Hackintosh community and developers of OpenCore and kexts used in this EFI.

ASH
