# rpi-eeprom releases
This page provides links to the production and development release images for the Raspberry Pi 4 bootloader EEPROM. Normally, the 
bootloader is automatically updated after an APT update via the [rpi-eeprom-update](https://www.raspberrypi.org/documentation/hardware/raspberrypi/booteeprom.md)
utility. However, it's sometimes more convenient to use a recovery image to program the EEPROM with default settings for a given release, rather than updating via Linux.

## Release notes
Release notes are available [here](https://github.com/raspberrypi/rpi-eeprom/blob/master/firmware/release-notes.md).

## Recovery image
The latest production recovery image is [2020-04-16](https://github.com/raspberrypi/rpi-eeprom/releases/tag/v2020.04.16-137ad). This
is the version selected by the [Raspberry Pi Imager](https://www.raspberrypi.org/downloads/).

## USB MSD BETA
The latest USB mass storage boot **BETA** recovery image is [2020-06-15](https://github.com/raspberrypi/rpi-eeprom/releases/tag/v2020.06.15-137ad).

For support please see this [forum thread](https://www.raspberrypi.org/forums/viewtopic.php?f=63&t=277007)

## Previous releases
All [previous releases](https://github.com/raspberrypi/rpi-eeprom/releases) are available here.

## Old EEPROM images
Recovery images are only created for production images or for major test releases e.g. USB MSD boot. Old bootloader images are periodically
removed from the APT package to reduce the disk space. The binaries can still be downloaded from Github [here](https://github.com/raspberrypi/rpi-eeprom/tree/master/firmware/old)
but are not supported and may fail to boot on newer revisions of the hardware.
For example, the Pi 4 8GB requires bootloader version 2020-04-16 or newer.
