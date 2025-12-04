---
title: Resources
tags:
- tag1
- tag2
---

## Code
This code runs on a Microchip PIC18F57Q43 Curiosity Nano using MCC generated drivers. It continuously reads an analog microphone input through the ADC, checks whether a button is pressed, and drives both an onboard LED and a digital output line accordingly. After initializing the system and ADC, the code enters an infinite loop where it samples the microphone (on analog channel ANA0) and compares the measured value to a defined threshold. If the sound level detected by the microphone exceeds the set threshold, the LED turns on and sends out a digital “yes” signal (logic high) is sent out on pin RA1 if the sound is below the threshold, both outputs remain low. This output signal is sent to and read by a seperate board.

The button on RB4 acts as a manual override. When pressed, it bypasses the microphone logic and forces both the LED and the output signal high after a short debounce delay. This allows the user to trigger the external signal or LED even when the microphone input is quiet. Overall, the code implements a simple sound-triggered digital output with a user-controlled override.


The zip folder of the project is available [here](https://github.com/alazaritt/alazaritt.github.io/releases/download/code/microphone_subsytem.X.zip).
