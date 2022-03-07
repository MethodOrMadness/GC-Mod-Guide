---
layout: single
title: "XenoGC Install"
---

{% include toc title="Table of Contents" %}

## About the xenoGC

The XenoGC Install is a lot easier than it first seems, though it does require a fair bit of soldering knowledge.

First, check out the [disassembly guide](/disassembly) before continuing! You need to have the RF Shield removed from the drive(looking at the PCB of the drive).

There are two types of installs, wired and wire-free. Since the xenoGC is an open-source modchip(meaning anyone can make it), it's been cloned countless times, and the specifications of the pcb might be off. For this reason we personally recommend a wired install.

## Installing

### Wire-free install

![solder points](/images/xenogc/install.jpg)

### Wired install

Refrencing the image below, use some small wire like 30 or 32awg magnet wire for the data wires and 22awg for power and ground(power is pad 10 and ground is pad 1 in the image below)

![alt solder points](/images/xenogc/altpoint.webp)

## Testing / Troubleshooting

When you power on the cube you should see a red LED light up and then turn green(or turn orange depending on the version). this indicates the drive has been patched and *should* read burned / out of region discs. If you aren't using out of region(but official) discs but instead burned media, proceed to the next step

### Laser adjustment

Typically this step is required, you want to turn the potentiometer on the cube to lower the resistance, we recommend going about 10ohm at a time. use a multimeter to verify the correct resistance.