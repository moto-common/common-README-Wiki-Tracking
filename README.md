# Motorola Common Project
The Motorola Common project aims to support AOSP development for all Motorola devices (4.14+) under a set of common trees. This approach was chosen in order to make bringups of new Motorola devices easier and allows fixes to be shared throughout all supported targets. 

## Device Support
Support for individual devices is added as long as a developer steps up to create the initial trees, further development from there is trivial. As part of the moto-common project, scripts handle the detection of fingerprint and  other device specific hardware in order to make bringups and device maintainence easier.

### Is my device supported?
Refer to the table [here](../../../../moto-common/android_device_motorola_targets)

## Rom Support
Support for different ROMs is handled in device/motorola/targets where generic
ROM makefiles are placed in rom/ and update_rom_device_symlinks.sh is called
to create the rom_device.mk files for all devices in the devices/ directory.

## Additional Information
For additional information please visit the Wiki tab of this repository or
click [here](https://github.com/moto-common/common-README-Wiki-Tracking/wiki)

## Copyrights
Copyright (C) Electimon 2023

Copyright (C) Sony Mobile Communications 2014

