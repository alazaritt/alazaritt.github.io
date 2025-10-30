---
title: Welcome
tags:
- tag1
- tag2
---

<center>
<font size= "6">Arianna Lazaritt's Datasheet</font><br>
as part of<br>
<font size= "8"> Sound and Motion Activated Light</font><br>
for<br>
<font size= "5"> Team 205 </font><br>


**Submission: 10, 27, 2025**
</center>


## Introduction

This datasheet provides an overview of the sound detection board, a key component within my team's hands-free lighting system, explaining its design, functionality, and integration within the overall project. It includes a block diagram illustrating how the microphone, operational amplifier, and microcontroller interact to detect and process sound, explanations of component selection, the circuit schematic, and the board’s power budget. This document should serve as a technical reference and provide a clear understanding of the board’s operation and its contribution to the system’s automatic lighting function. 

### Project Summary

Our full team project focuses on creating a hands-free lighting system using four interconnected PCBs. The system includes a sound detection board that responds to audio cues and a motion detection board that senses movement. When either board is activated, a signal is sent to a control board, which processes the inputs and determines whether to turn the lights on or off. The control board then communicates with the light board, which powers and manages the illumination, providing an efficient and convenient automatic lighting solution.

### My Contribution

My part of the overall project focuses on the sound detection board. It uses a microphone to capture specific audio cues, which is then amplified by an op-amp. This signal is then processed by a microcontroller that will determine if the detected sound has reached a certain threshold to then send a signal to a separate controls board. That separate board will take the signal from my sound detection board and relay it to a light control board to either turn on or off a set of lights. 

The successful development of this module is critical to the overall performance of the team project. By providing accurate and timely sound detection, my work ensures that the lighting system can respond reliably to auditory cues. This complements the motion detection module and enhances the system’s functionality, contributing directly to the team’s objective of creating an intelligent, hands-free lighting solution. More details on project requirements, user needs, and other aspects of the overall system can be found in the [team report.](https://egr304-team-205-2025-f.github.io/EGR304-2025-F-205.github.io


To see how each major component within the subsytem communicates and interacts, see the [Block Diagram](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/01-Block-Diagram/Block-Diagram.md ) section of the datasheet.

For additional reasoning of why individual components were selected, please see the [Component selection](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/02-Component-Selection/Component-Selection.md) section of the datasheet.

To review the details listed of the material used to construct the subsection, you can review it in the ["BOM"](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/03-BOM/BOM.md) section of the datasheet.

For a more in depth overview of the subsystem and to access associated files with it, review the [Schematic](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/04-Schematic/schematic.md) section of thie datasheet.

To see how power was taken into consideration and a calulated current draw of all components within the system, see the [Power Budget](https://github.com/alazaritt/alazaritt.github.io/blob/main/docs/05-Power-Budget/Power-Budget.md) section of the datasheet.

