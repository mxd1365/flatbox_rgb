# Flatbox: Low profile hitbox-layout fightstick

This repository contains 3D-printable models, PCB design files and code needed to make an arcade controller that looks like this:

![Assembled Flatbox](hardware-rev2/images/Flatbox-rev2b-finished-product.jpg)

There are four major versions of the Flatbox. They all use Kailh low profile (choc v1) mechanical keyboard switches. The table below lists their main features. See the README for each version for details on how to make them.

version | [rev1.1](hardware-rev1.1) | [rev2](hardware-rev2) | [rev3](hardware-rev3) | [rev4](hardware-rev4) | [rev4_rgb]
------- | ------------------------- | --------------------- | --------------------- | --------------------- | ---------------------
case dimensions | 218x128x10mm | 218x130x10mm | 218x130x10mm | 218x130x10mm | 218x130x10mm
compatibility (using provided firmware) | PC, PS3 | PC, PS3 | PC, PS3, PS4 | PC, PS3 | PC, PS3
add-on board | Arduino Pro Micro | - | [Brook PS3/PS4](https://www.brookaccessory.com/detail/58690501/) | -
onboard chip | - | ATmega32U4 | - | RP2040 | RP2040
port | micro USB | USB-C | USB-C | USB-C | USB-C
SMT assembly required | no | yes | yes | yes | yes
firmware | [ATmega32U4](firmware-atmega32u4) | [ATmega32U4](firmware-atmega32u4) | [Brook](https://www.brookaccessory.com/download/PS3/) | [RP2040](firmware-rp2040) | [RP2040_RGB](firmware-rp2040_rgb)
