Device configuration for Vsmart Joy 3
==================================
## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core 1.8 GHz Cortex-A53
Chipset | Qualcomm SDM632 Snapdragon 632
GPU     | Adreno 506
Memory  | 2GB , 3GB , 4GB
Shipped Android Version | 9.0 (Pie)
Internal Storage | 32GB , 64GB
microSD | Up to 64GB (dedicated slot)
Battery | 5000 mAh
Dimensions | 165.13 x 76.4 x 9.19 mm
Display | 1600 x 720 pixels, 6.5-inch IPS LCD
Rear Camera  | 13 MP + 8 MP + 2 MP
Front Camera | 8 MP

### Introduction
This is the device tree to build LineageOS 19.1 for the Vsmart Joy 3.

Originally it was started with the [base configuration of Fairphone 3](https://github.com/LineageOS/android_device_fairphone_FP3)
, [Motorola's SDM632 platform](https://github.com/LineageOS/android_device_motorola_sdm632-common) and the [river configuration](https://github.com/LineageOS/android_device_motorola_river) was used as an example.
Some [settings](https://github.com/hyperion70/twrp_device_vsmart_casuarina) are taken from hyperion70's TWRP device tree.

Thanks to Fairphone 3 community for amazing work

### Current Status
* Device boots. :heavy_check_mark:
* Adb can be accessed. :heavy_check_mark:
* Working things after quick test:
  * Display / Touchscreen :heavy_check_mark:
  * RIL :heavy_check_mark:
  * Device encryption :heavy_check_mark:
  * GPS :heavy_check_mark:

### Known Issues
These things are untested or known not to work:
* Camera
* Sound
* Wi-Fi
* Bluetooth
* Fingerprint

### Kernel Source
The kernel used is a prebuilt kernel, taken from V430A_OPN_U_B13_210315
