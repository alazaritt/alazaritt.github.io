---
title: Individual Block Diagram a.l
tags:
- tag1
- tag2
---

## Overview
This block diagram outlines the audio sensor subsystem for a motion- and audio-activated light. The board includes a microphone for detecting sound, with an op-amp used to tune the analog signal before it is read by the onboard ADC of the PIC18F57Q43 microcontroller. A digital output signal is then sent to a teammate's board to trigger a response.
The subsystem operates at 5V of power via a voltage regulator. A single reset button is included as a digital input. Communication with the main control board is handled through an 8-pin ribbon cable, using one digital signal line and ground. The block diagram documents all major connections, power domains, signal directions, microcontroller use, and team interconnections.


## Sound Board Block Diagram 

![Individual Block diagram ](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/01-Block-Diagram/individual%20block%20diagram.drawio.png?raw=true)
