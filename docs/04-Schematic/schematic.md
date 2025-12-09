---
title: Schematic
---

## Overview

This schematic defines the motor subsystem, including power regulation, override controls, microcontroller interfaces, and the H-bridge motor driver. Its purpose is to provide reliable bidirectional motor control while supporting testing and integration with the overall system.

The power section converts the 9V wall supply into a stable 5V line using an LM7805 regulator, which powers the PIC microcontroller, H-bridge, LEDs, and switches. Bypass capacitors are included to reduce noise and ensure stable operation.

The microcontroller uses pins RB3 and RB0 to send forward and reverse control signals to the H-bridge. Sensor signals from other subsystems connect through the 8-pin ribbon headers, and several extra analog and digital pins are broken out for debugging and future expansion. An LED indicator provides simple visual feedback.

Two override switches allow the user to manually force forward or reverse motor motion for testing or safety checks. Each switch outputs a 5V control signal when pressed.

The H-bridge (FAN8100N) receives these control signals and drives the Pololu DC motor in either direction. Protection diodes and bypass capacitors help manage noise from the motor.

<br>

<img width="2472" height="1012" alt="image" src="https://github.com/user-attachments/assets/f2a4a16a-9b52-4613-b65d-0f289db13184" />













**Figure 1:** Showing the schematic for the motors that control the water valve.


## Resouces

The schematic as a PDF download is available ,[*here*](https://github.com/user-attachments/files/23864050/Subsystem-schematic-design-RSC-.pdf), and the Zip folder of the project [*here*](https://github.com/user-attachments/files/23014451/Subsystem-schematic-design-RSC-.zip)


