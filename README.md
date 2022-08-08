# ASUS X515JA Hackintosh i5 10th gen
<img src="https://github.com/Levonhard/X515JA-Hackintosh/blob/main/screenshot-monterey.png">

## ASUS X515JA-EJ1792W SPECS

| COMPONENTS | MODEL                                 |
|------------|---------------------------------------|
| CPU        | Intel Core i5 1035G1                  |
| RAM        | 8 GiB@2667MHz DDR4                    |
| iGPU       | Intel(R) UHD Graphics G1              |
| WiFi       | Intel Wireless-AC 9461                |
| Storage    | NVME 256 GiB                          |

### WHAT WORKS
- [x] Intel integrated graphics
- [x] USB
- [x] Webcam
- [x] Brightness control
- [x] Battery percentage
- [x] TouchPad w/ Advanced Gestures
- [x] Intel WiFi
- [x] Speakers
- [x] Headset Combo Jack
- [x] Apple Services (iCloud, Apple Music, Apple TV, others..)
- [x] Intel Bluetooth
- [x] Sleep Mode
- [ ] HDMI

### NOT TESTED
- Airdrop

## GUIDE
### BIOS SETUP
- Disable "Fast Boot"
- Disable "Secure Boot"
- Disable "VT-d" and "VT-x"

### SETUP
- Generate your own SMBIOS

### POST-INSTALL SETUP
- For headset combo jack to work you have to run the script provided here https://github.com/hackintosh-stuff/ComboJack, the necessary kext is already present on this EFI.
