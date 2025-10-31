---
title: Schematic
---

## Overview

The schematic illustrates how the system effectively converts audio input from a microphone into a control signal for a separate board to operate lights, fulfilling both user needs and product requirements. 

This schematic shows an individual audio sensor subsystem designed to detect and process sound reliably. It consists of three main sections, a microphone with an amplifier, a regulated power supply, and a microcontroller, each supporting user needs and product requirements for accuracy, compatibility, and responsiveness.

The microphone and amplifier convert sound into an electrical signal and boost it to a usable level. The microphone generates a small AC voltage, which the op-amp amplifies before sending to be processed by the microcontroller. The integration of the op-amp stabilizes the signal and minimizes noise, ensuring the microcontroller receives a clean, accurate input. This section fulfills the need for precise sound detection and reliable performance in variable sound conditions.

The power supply circuit provides the required 5V throughout the system. It includes a barrel jack for external power, a voltage regulator for steady output, and protection components such as a fuse and capacitors. This ensures consistent operation and protects the circuit from overvoltage or current surges.

The microcontroller subsystem processes the amplified sound signal, detects when it exceeds a threshold, and provides output or feedback. A push button allows for any necessary manual control, while an LED indicator provides immediate visual feedback and aids in any needed debugging. UART and header connections offer expandability and debugging options. Power filtering capacitors and protection diodes ensure stable, noise-free operation.



![schematic](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/04-Schematic/individual%20schematic%20ss.png?raw=true)
**Figure 1:** Sound board schematic


## Resouces

The schematic as a PDF download is available [*here*](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/04-Schematic/individual%20subsystem.pdf), and the Zip folder of the project [*here*](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/04-Schematic/individual%20subsystem.zip).
