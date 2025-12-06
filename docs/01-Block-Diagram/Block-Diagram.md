---
title: Individual Block Diagram
tags:
- tag1
- tag2
---

## Overview
This block diagram outlines my subsytem, which is the sound detection subsystem for an audio-activated light. The board includes a microphone (sensor) for detecting sound, with an op-amp used to tune the analog signal before it is read by the onboard ADC of the PIC18F57Q43 Curiosity Nano microcontroller. A digital output signal is then sent to a teammate's board to trigger a light as well as to make a motor stop spinning.

9V is coming throught the barrel jack from the external power supply, however, the subsystem operates at 5V of power. These 5V can be provided via the voltage regulator within the circuit, or through power and ground being fed through the ribbon connector by a teammate's board. An override button to turn on the light regardless of sensing is included as a digital input. Communication with the main control board is handled through an 8-pin ribbon cable, using one digital signal line. The block diagram documents all major connections, power domains, signal directions, microcontroller use, and team interconnections.

Each element of the block diagram contributes to key aspects of my team's product requirments. The main idea of our product is that a light is triggered in a hands-free way, specifically by using a microphone (as shown in the image below). The signal from the microphone goes through the op-amp to ensure that a clean signal is read, as our product requirments aim to minimze false triggers. The microcontroller is responsible for analyzing the  input signal and converting it to a digital output signal to toggle the light. The manual override button was also a key part of our product requirements, as we wanted consumers to have the option to turn a light on even if the room is lit or if sound is not detected.

## Diagram Link
A direct link to the source file of the following block diagram can be found [here](https://github.com/alazaritt/alazaritt.github.io/releases/download/blockdiagram.io/individual.block.diagram.drawio).

## Sound Board Block Diagram 

![Individual Block diagram ](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/01-Block-Diagram/individual%20block%20diagram.drawio.png?raw=true)
