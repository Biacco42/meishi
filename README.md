# Meishi

**Meishi - The micro macro keyboard.**

The micro macro keyboard which has only four keys for self made keyboard beginners. 

![Meishi](https://raw.githubusercontent.com/Biacco42/meishi/readme/readme_image/P1210037.JPG)

# Parts

- **1** Meishi PCB
- **1** 5V/16MHz Pro Micro compatible boards
- **4** 1N4148 diodes
- **4** [Switches of your choice](https://mechanicalkeyboards.com/shop/index.php?l=product_list&c=107)
- **1** Tact switch
- **4** Cushion rubber

## Mount the Diodes

**Double check your work**. Black lines should be facing the square pad.

## Mount switches

Mount switches on PCB.

## Mount the Pro Micro

Meishi PCB is symmetrical. The PCB logo side up, mount Pro Micro upside up.

## Attach cushion rubber

Attach cushion rubber on PCB buttom side.

## Flash QMK Firmware

QMK firmware for Meishi now abilable on [this repo at meishi branch](https://github.com/Biacco42/qmk_firmware/tree/meishi).
This document doesn't cover how to build QMK. Prease refer to [QMK documents](https://docs.qmk.fm/).

Conntect the keyboard by usb cable to PC and run

```
$ make meishi:default:avrdude
```

will build and try to flash your firmware. Follow the instractions that require to reset the Pro Micro.

This process may require privileges.

## All have done
