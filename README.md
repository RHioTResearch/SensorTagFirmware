# SensorTagFirmware
Custom firmware images for the CC2650 based [TI SensorTag](http://www.ti.com/ww/en/wireless_connectivity/sensortag2015/)

The current SensorTagSuper.hex image is a customization of the SensorTag project found in the [TI BLE-STACK-2-1-1](http://www.ti.com/tool/ble-stack) that always advertises when not connected, and does so at a rate of 1s rather than the default of 100ms.

It is a SuperHex File as described in:
[CC2650 SensorTag User's Guide#Building_the_SensorTag_Firmware](http://processors.wiki.ti.com/index.php/CC2650_SensorTag_User's_Guide#Building_the_SensorTag_Firmware)

To flash this version of the firmware, you need the $15 [cc-devpack-debug](http://www.ti.com/tool/cc-devpack-debug) and the free [SmartRF Flash Programmer v2](http://www.ti.com/tool/flash-programmer).

In progress is a version of the firmware that can be loaded via the TI SensorTag apps for Android/iOS using the OAD feature.
