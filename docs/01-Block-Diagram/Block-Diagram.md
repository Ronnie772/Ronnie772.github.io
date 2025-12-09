---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview
This block diagram represents the motor subsystem for the Garden Buddy, The subsystem operates across an unregulated 9V input supplied by the barrel jack and a regulated 5V level produced by the LM7805T voltage regulator. The 9V input powers the regulator, and the resulting 5V rail is used to supply the PIC18F57Q43 microcontroller, the H-bridge driver (FAN8100N), and the supporting digital electronics. This ensures that all control logic and motor-drive signals operate within safe and consistent voltage levels.

The microcontroller outputs two PWM-capable signals from pins RB3 and RB0, which correspond to the forward and reverse control lines of the H-bridge. These PWM signals allow for fine-grained motor control, including adjustments to speed and torque. The microcontroller also uses digital I/O pins such as RF4 and RC0 to interface with additional system inputs and to provide status feedback, such as driving the subsystem’s red LED indicator.

Two override switches are included in the design to support system checks and manual control during testing. Each switch provides a 5V digital signal that can override the microcontroller’s PWM inputs when necessary, enabling direct control of the motor driver. These switches contribute to safer development and troubleshooting by allowing the user to verify motor behavior independently of firmware.

The H-bridge itself receives the PWM inputs and produces a two-pin 5V output that drives the Pololu 2371 motor.

Overall, this subsystem meets product requirements by providing reliable and modular motor control that is compatible with both automated firmware-based operation and manual testing.

<br>

<img width="1160" height="768" alt="image" src="https://github.com/user-attachments/assets/5befd2f7-8962-4bba-9713-6f62fa31652c" />

<br>

downloadable pdf available [*here*](https://github.com/user-attachments/files/23423738/block-diagram-RSC.drawio.1.pdf).
