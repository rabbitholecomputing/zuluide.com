<img src="assets/img/ZuluIDE-V2-Compact-Rev2025a-front-iso-nobg.webp" alt="ZuluIDE V2 Compact product photo">

ZuluIDE™ is a hardware interface between IDE bus and SD cards. Currently it supports emulating ATAPI CD-ROM drives, Zip Drive 100, and a generic removable drive by providing access to image files stored on SD card. 

ISOs and bin/cue files are stored on a standard FAT32 or exFAT-formatted SD card. SDXC cards of up to 512GB are supported.

## ZuluIDE Features

* [Firmware-updatable](https://github.com/ZuluIDE/ZuluIDE-firmware/releases) - as simple as copying a file to your SD card
* Emulates IDE/ATAPI CD-ROM drives of any size
  * CD Audio playback emulation via optional DAC hat
* Emulates ZIP100 ATAPI removable media
  * Compatible with Roland SP-808/808EX
* Emulates rigid ATA/IDE hard drives (up to ATA/33)
  * Raw image files (.bin/.hda/.hdf)
  * Virtual Hard Drive (VHD V1) image files
* Supported transfer modes:
  * [PIO modes](https://en.wikipedia.org/wiki/Programmed_input%E2%80%93output) 0-3
  * [Ultra DMA](https://en.wikipedia.org/wiki/UDMA) 0-1
  * **ATA/33** (ZuluIDE V2 only) at up to **28** megabytes per second 
* Hardware eject button and pin header for remote eject button
* DIP switches for control of:
  * Primary/Seconday device selection
  * Cable Select
  * Debug mode/logging
* Activity LED and pin header for remotely-mounted/front-panel LED
* Expansion header for optional web-based UI
* Qwiic 4-pin connector for hardware UI control board
* Debug header for [Raspberry Pi Debug Probe](https://www.raspberrypi.com/documentation/microcontrollers/debug-probe.html)
* [Open-source firmware](https://github.com/rabbitholecomputing/zuluIDE-firmware), licensed under the GPLv3
