---
layout: single
title: "Picoboot"
---

{% include toc title="Table of Contents" %}

Picoboot is an IPL modchip based on the 4$ raspberry pi pico MCU board.
* You will need a [raspberry pi pico](https://www.raspberrypi.com/products/raspberry-pi-pico/) with an SD2SP2 or SD Gecko

## Features
* boots automatically any DOL app of your choice on startup
* you can assign Buttons `X`, `Y` or `B` to a .dol file if you want, normally it will boot into `ipl.dol`

## Modchip Programming

* Go to the [latest release](https://github.com/webhdx/PicoBoot/releases/latest) and download the `picoboot.uf2` file.
* connect Raspberry Pi Pico board to your computer while holding `BOOTSEL` button pressed
* Drag and drop picoboot.uf2 file to `RPI-RP2` device
* green LED will light up and the pico itself ejects automatically

## Hardware Installation
If you installed your PicoBoot according to the [Wiring Diagrams](/picoboot#wiring-diagrams), go to [Software Installation](/picoboot#software-installation)
* Videos for reference:
  - [MachoNachoProductions](https://www.youtube.com/watch?v=qwL4ZSa0xMo)
  - [RockerGaming](https://www.youtube.com/watch?v=lfMTLEM0yeQ)
  - [ModzvilleUSA!](https://www.youtube.com/watch?v=W_9-mSBMBJ4)

### Required Materials:
  * A soldering iron
  * 5 Wires(I harvested wires from breadboard wires by cutting the connectors off and stripping them)
  * Flux
  * Solder
  * (HIGHLY Recommended, to prevent shorts) Kapton Tape

### Wiring Diagrams
#### DOL-001
![DOL-001 install](/images/picoboot/001.jpg)

#### DOL-101
![DOL-101 install](/images/picoboot/101.jpg)

## Software Installation
* Format your SD card to FAT32 or exFat
* Download [swiss_rXXXX.7z](https://github.com/emukidid/swiss-gc/releases/latest) and extract it
* go to the `swiss_rXXXX/dol` folder, grab the `swiss_rXXXX.dol` file and rename it to `ipl.dol`
* copy the file to the root of your SD card.
  - To assign a .dol file to the buttons, rename them to `x.dol`, `y.dol` or `b.dol`
  - if no .dol file is present, it will boot into gamecube menu
