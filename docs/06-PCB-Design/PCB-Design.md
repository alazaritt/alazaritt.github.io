---
title: PCB Design
tags:
- tag1
- tag2
---

## Overview
My PCB is responsible for detecting environmental sounds through a microphone, amplifying the signal with an op-amp, and sending a processed digital signal to a seperate board via a microcontroller. The PCB layout ensures that the microphone and op-amp are properly placed for minimal noise, and that the microcontroller’s power and ground connections are strong enough for reliable signal transmission. 

In order to safely carry current, all power and ground traces are 40 mils, which also reduces voltage drops. All other signal traces, like those connecting the microphone, op-amp, and microcontroller I/O pins, are 20 mils, which is sufficient for lower current signals. Bypass and decoupling capacitors have been placed as close as possible to the microcontroller power pins, with shorter traces to reduce noise. This design ensures reliable detection of sound events while maintaining manufacturability and signal strength.


## PCB Design Layout

Both Layers
![figure1](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/06-PCB-Design/pcb%20both.png?raw=true)

Top Layer
![figure2](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/06-PCB-Design/pcb%20cu.png?raw=true)

Bottom Layer
![figure3](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/06-PCB-Design/pcb%20bottom.png?raw=true)

The zip folder of the project is available [here](https://github.com/alazaritt/alazaritt.github.io/releases/download/schematiczip/individual.subsystem.zip), the zip folder of the gerber files are available [here](https://github.com/alazaritt/alazaritt.github.io/releases/download/gerberfiles/AriannaLazaritt205.zip), and a pdf download of the PCB can be found here: [top layer](https://github.com/alazaritt/alazaritt.github.io/releases/download/pcbpdf/pcb.pdf), [bottom layer](https://github.com/alazaritt/alazaritt.github.io/releases/download/pcbpdfcont/gnd.pdf)., [both layers](https://github.com/alazaritt/alazaritt.github.io/releases/download/pcbpdfcont/all.pdf).
