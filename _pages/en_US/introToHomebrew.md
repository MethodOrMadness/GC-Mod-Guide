---
layout: single
title: "Introduction to Homebrew"
---
{% include toc title="Table of Contents" %}
## First, what is homebrew?
Homebrew is a general term that refers to code running on a device that wasn't designed to be user programable.

There is no single "homebrew" since it's a genre of software

Most of the time you use Swiss, an all-in-one homebrew utility for the Nintendo GameCube.

## How can I do it?

There are three (easy and modern) ways to boot into homebrew.

- The first being a modchip such as the Picoboot to boot directly into e.g. Swiss
  * You will need some soldering experience to install it
- The second is using Save Game Exploits, but in order to use it you need a memory card with your exploit
  * either a gamecube/wii with homebrew to create it or you can buy an memory card with your exploit already installed.
- The third is an ODE, or an optical drive emulator.
  * currently, at the time of writing, the GCLoader (only ODE available) is out of stock. We advise against opting for the cloned "GCLoader Lite's" you see on ebay as these have lots of issues.
- If you are interested, you can check out [some other exploits](/introToHomebrew#legacy--complicated) available for the Gamecube

## Methods

### Picoboot IPL Replacement
- The most practical way would be a IPL replacement modchip from [webHDX](https://github.com/webhdx/picoboot) that instantly boots swiss(or other homebrew) on startup!
  * Picoboot runs on a 4$ microcontroller using 5 wires and a drag-and-drop programming from any computer
  * See the [Wiki](https://github.com/webhdx/PicoBoot/wiki) page to install the modchip 

### Game Save Exploits
- This is the second way, it is usually free (if you already have the game) or cheap and generally easy to setup
  * You can find more instructions on the [save game exploit](saveExploits) page!

### ODE(GCLoader)
- This is probably the easiest to do long term, short term requires a bit of knowledge on the cube. You essentially replace the disc drive with an SD card. This means you can autoboot a Swiss disc iso, but you can no longer use actual discs



## Legacy / Complicated

### XenoGC
Checkout [this page](xenoInstall)

* only if you want to have a region-free console to use for example japanese game disks or burned disks
* requires soldering a modchip into the disk drive to boot burned disks (in this example a Swiss-Disk)
* not recommended as the berrycube is easier to install, costs the same as the xenogc and the drive does not wear out

### PSOLoad

Checkout [this page](/PSOLoad)

* requires a BBA and a copy of PSO Episode 1/2

### SD Media Launcher / Action Replay

Checkout [this page](/sdMediaLauncher)

* Requires a disc and sd gecko purchased from [here](https://www.codejunkies.com/products/sd-media-launcher__ef000580v.aspx)
