# Meishi

**Meishi - The micro macro keyboard.**

The 4-key micro macro keyboard for self-made keyboard beginners.

![Meishi](https://raw.githubusercontent.com/Biacco42/meishi/readme/readme_image/P1210037.JPG)

# Parts

- **1** Meishi PCB
- **1** 5V/16MHz Pro Micro compatible boards
- **4** 1N4148 diodes
- **4** [Switches of your choice](https://mechanicalkeyboards.com/shop/index.php?l=product_list&c=107)
- **1** Tact switch
- **4** Rubber pads

## Mount the Diodes

Meishi PCB is symmetrical. The side with the logo is the top.
**Double check your work**. Black lines must be facing the square pad.

## Mount switches

Mount switches on the top side of the PCB.

## Mount the Pro Micro

Mount the Pro Micro on the top side of the PCB with the Pro Micro's USB facing up. (Please refer to the image)

## Attach rubber pads

Attach the rubber pads on the bottom side of the PCB.

## Flash QMK Firmware

QMK firmware for Meishi is available in [this repo on the meishi branch](https://github.com/Biacco42/qmk_firmware/tree/master/keyboards/meishi).
This readme document does not cover how to build QMK. Please refer to the [QMK documents](https://docs.qmk.fm/).

Connect the keyboard to the PC via USB and run the following:

```
$ make meishi:default:avrdude
```

It will build and try to flash your firmware. Follow the instructions that require to reset the Pro Micro.

This process may require elevated privileges.

## You're all done!
