# Dell Latitude E7470 macOS Big Sur (OpenCore)
forked from [adityabakare/macOS-Dell-Latitude-E7470](https://github.com/adityabakare/macOS-Dell-Latitude-E7470)

## My hardware

* Processor: Intel Core i7-6920HQ
* Graphics: Intel HD Graphics 530
            AMD Radeon RX 580
* Memory: 16GB 2133MHz DDR4 SODIMM
* Display: 17.3" FHD (2560x1440) with ELAN Touchscreen
* Soundcard: Realtek ALC293
* Storage: 512GB M.2 SATA SSD
* WiFi + BT: Intel Dual Band Wireless-AC AX200
* Fingerprint Reader: No
* Camera: 1920x1080 FHD Webcam
* Keyboard: Backlit Keyboard
* Trackpad: ALPS Touchpad

## What's Working

- [x] Intel HD 530 Graphics `incuding graphics acceleration`
- [x] All USB ports
- [x] Internal camera
- [x] WiFi using [AirportItlwm](https://github.com/OpenIntelWireless/itlwm)
- [x] Bluetooth using [IntelBluetoothFirmware and IntelBluetoothInjector](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)
- [x] Shutdown / Reboot / Sleep / Wake
- [x] Speakers and headphones jack
- [x] Intel Gigabit Ethernet
- [x] iMessage, FaceTime, App Store
- [x] HDMI(with audio passthrough)
- [x] Keyboard and Trackpad(two finger vertical swipes)
- [x] DRM(Works with Google Chrome. Tested with Prime Video and Netflix.)

## What's not working

- [ ] Multitouch gestures for ALPS touchpad.

## Untested

* miniDP
* Card Reader

## Current configuration

* macOS: Big Sur 11.1 Beta版(20C5061b)
* OpenCore: 0.6.3

## Update Instructions

To Update to Big Sur from Catalina, just replace the previous Catalina EFI with this one and update normally.
