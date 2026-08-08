# ChimeraTool Changelog

---

## [34.66.0907] — 2025-09-07

### Added
- Samsung Galaxy S25 series: full support (Flash, IMEI, FRP, Network Unlock, MDM)
- Samsung Galaxy A55 and A35 flash support via latest firmware packages
- MediaTek Dimensity 9300 chipset full module
- New UNISOC T820 module with IMEI repair
- EFS mount via ADB for post-flash verification (experimental)

### Fixed
- EFS backup failure on Galaxy A35 / A55 with One UI 6.1.1
- Driver conflict when Samsung USB and Qualcomm Diag drivers are installed simultaneously
- MTK Brom connection spontaneously dropping on hosts with USB 3.2 Gen 2 controllers
- IMEI write partial failure on dual-SIM Exynos devices when SIM2 slot is empty

### Improved
- Samsung Exynos flash speed improved by 25% through optimized block write size
- FRP removal reliability on Android 13 and 14 significantly improved
- Device auto-detection now covers model variants not in the local database (uses cloud lookup when connected)

---

## [34.65.0801] — 2025-08-01

### Added
- Xiaomi HyperOS FRP bypass for Xiaomi 14 and 14 Pro
- Samsung Galaxy Ring device detection (wearable, limited to FRP and pairing reset)
- UNISOC T616 full flash support

### Fixed
- Binary counter display showing incorrect value on Galaxy S22 Ultra SM-S908U1 (US unlocked)
- Pattern removal failure on certain MTK devices running Android 12L

---

## [34.64.0610] — 2025-06-10

### Added
- MediaTek Dimensity 7050 complete chipset support
- Samsung One UI 6.0 FRP bypass update
- SPD T700 tablet module (flash + FRP)

### Fixed
- Driver installer crashing on Windows 11 24H2 insider builds
- Firmware file path validation not accepting Cyrillic folder names

---

## [34.63.0415] — 2025-04-15

### Added
- Galaxy A15 5G (SM-A156) and A15 4G (SM-A155) support
- Realme C65 4G (UNISOC) FRP bypass

### Improved
- MTK Brom connection reliability on USB-C only systems (USB 3.x)
- Interface startup time reduced from 8 seconds to 4.5 seconds

---

## [34.62.0212] — 2025-02-12

### Added
- Samsung Galaxy S24 FE flash and FRP support
- UNISOC T606 IMEI repair (dual SIM)

### Fixed
- ADB-based reset not reconnecting device automatically after reboot
- Incorrect progress bar behavior when flashing firmware over 10 GB
