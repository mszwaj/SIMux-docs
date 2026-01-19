<!-- SPDX-License-Identifier: LicenseRef-Proprietary
SPDX-FileCopyrightText: Copyright (c) 2025 Maciej Szwaj
See LICENSE file in the root directory for full license terms -->

# SIMux - SIM Multiplexer

## Introduction
SIMux lets users to switch between up to 4 SIM cards under one target device.\
Currently allows to choose 1 out of 4 nanoSIM cards or switch SIM off.\
It is possible to use it with just a button on board or to use on any OS which supports _UART_ or _USB CDC_ connectivity.\
Checked on:
- Windows 11 with Putty and MobaXterm
- Linux Ubuntu 24.04 with minicom
- Android 15 and 16 with [Serial USB Terminal](https://play.google.com/store/apps/details?id=de.kai_morich.serial_usb_terminal&hl=pl) app

No need to install any additional drivers.

## MVP will (UPDATED: 20251225):
1. Support Single SIM choosing 1 out of 4, or no SIM at all
2. Give possibility to *RESET* device, *GETSN* to check SN, *SETSN=* to set SN and check current MUXes *STATE*
3. Give possibility to Choose SIM card via serial monitor (115200 baud rate) and physical button concurrently
4. Show visually which SIM card is chosen by adding XIAO built-in LED's blinking while changing
5. Let user to connect up to 8 boards with only one MCU and control all of them by connecting only one USB-C cable
6. Be designed in KiCad 9.0 (or later)
7. Work based on Seeeduino XIAO SAMD21
8. Be documented properly:
• fw will have comments
• hw will have all designed files and BoM
• there will be simple manual - how to use with serial monitor or only by button

## For Testers
### Changelog and binary

### Flashing

### Logging


## Documentation
User manual or documentation can be found in the /docs folder.

## License
This project is proprietary. Testing access does not grant rights to hardware designs or firmware code. For full license please check [LICENSE](LICENSE)