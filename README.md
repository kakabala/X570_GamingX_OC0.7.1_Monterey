# Hackintosh Monterey Guide for Gigabyte X570 Gaming X (OpenCore 0.7.1)

### Tested:
- Monterey Beta 3

## Hardware

| **Component**    | **Model**                                       |
| ---------------- | ----------------------------------------------- |
| CPU              | AMD Ryzen 3700X                                 |
| Motherboard      | Gigabyte X570 Gaming X                          |
| RAM              | 32GB HyperX Predator DDR4 (HX432C16PB3AK2/32)   |
| GPU              | MSI Vega 56 Air Boost 8G                        |
| Audio Chipset    | ALC-887                                         |
| Ethernet         | Realtek RTL8111                                 |
| WiFi & Bluetooth | Broadcom BCM94360 PCIe card (Bluetooth + Wi-Fi) |
| OS Disk (NVMe)   | Samsung 970 EVO NVMe 500G                       |

**macOS version**: 12.0 Beta 3 (21A5284e) \
**OpenCore version**: 0.7.1


### What's Working/What's Not

##### Working
- Ethernet
- Onboard Audio (including digital audio)
- APFS
- Sleep/Wake
- All USB ports at 3.x speed
- iMessage
- App Store
- Facetime
- APFS
- Handoff
- Bluetooth & Wi-Fi (via Broadcom adapter)
- Airdrop
- AirPlay
- Continuity
- ALL DRMs:
  - iTunes Movies (FairPlay 1.x)
  - Netflix (FairPlay 2.x/3.x)
  - Some Amazon Prime content, but not all. (FairPlay 2.x/3.x)
  - Apple TV+ (FairPlay 4.x)
- Power Nap
- NVRAM


##### Not Yet Tested
- FileVault


### Reference
- https://dortania.github.io/OpenCore-Desktop-Guide/


### Note
You are welcome to use my EFI folder. However, make sure you set the following:

- SystemSerialNumber
- SystemUUID
- MLB
