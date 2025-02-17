# Matter Software Artifacts

This page provides links to pre-built software image "artifacts" that can be
used to set up the Matter Demo for the Thread and Wi-Fi use cases.

<br>

## Matter Hub Raspberry Pi Image

The Matter Hub image is intended to be flashed onto an SD card for a Raspberry
Pi. The Matter Hub Image provides both an Open Thread Border Router and the
Matter chiptool. Note the image is ~10GB in size so depending on your internet
connection this download may take some time. Start the Matter Hub Raspberry Pi
image download here:

https://www.silabs.com/documents/public/software/SilabsMatterPi.zip

<br>

## Radio Co-Processor (RCP) Images

The Radio Co-Processor firmware is used to turn an EFR into an RCP that can be
used with a Raspberry Pi to allow the Raspberry Pi's Open Thread Border Router
to access the Thread network. Radio Co-Processor (RCP) images are available in
the Assets section of this page:

https://github.com/SiliconLabs/matter/releases/tag/v0.3.0

<br>

## Matter Accessory Device Images

The Matter Accessory Device Images are used to turn an EFR into a Matter device.
These are pre-built binary images for the Matter Demo. Matter Accessory Device
Images are located in the Assets section of this page:

https://github.com/SiliconLabs/matter/releases/tag/v0.3.0

<br>

## Matter Bootloader Binaries

If you are using the OTA functionality and especially if you are using an
EFR32MG2x device, you will need to flash a bootloader binary on your device along
with the application image. Bootloader binaries for all of the Matter supported
devices are available here:

https://github.com/SiliconLabs/matter/releases/tag/v0.3.0

<br>

## RS9116 Firmware

The RS9116 firmware is used to update the RS9116 - it can be found in the
repository you have cloned, at the following relative path from the `/matter`
directory, `./third_party/silabs/wiseconnect-wifi-bt-sdk/firmware`

<br>

---

[Table of Contents](../README.md) | [Thread Demo](../thread/DEMO_OVERVIEW.md) |
[Wi-Fi Demo](../wifi/DEMO_OVERVIEW.md)
