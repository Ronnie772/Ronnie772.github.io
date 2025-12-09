---
title: PCB - Design
---

## Overview
The PCB for Motor Subsystem of Garden Buddy project implements the PIC18F57Q43 Curiosity Nano, the FAN8100N H-bridge driver, and connectors for the Pololu DC motor and team sensor interfaces. A 9v barrel jack supplies power to the onboard LM7805 linear regulator, which generates the regulated 5v rail used by the microcontroller, H-bridge, indicator LED, and override switches. Additional components such as pull-down resistors, bypass capacitors, and the safety override switches are placed to ensure stable operation and simplify testing.

<br>

3D rendered PCB image (KiCAD)
<img width="782" height="961" alt="image" src="https://github.com/user-attachments/assets/85dab004-b246-45d7-8ec4-0592828a8b15" />

<br>

Top layer image of PCB (before soldering)
![before_soldering_front](https://github.com/user-attachments/assets/c054d14b-76f7-4f25-8c90-6d4bc91d6bdc)

<br>

Bottom layer of PCB (before soldering)
![before_soldering_back](https://github.com/user-attachments/assets/199a2b3c-edb9-4034-a2e2-eb95ebb4940e)

<br>

Top layer of the PCB (after partial soldering)
![after_soldering_front](https://github.com/user-attachments/assets/4d27d4cb-8b6d-423c-91e1-77934fec5f80)

<br>

Bottom layer of the PCB (after partial Soldering)
![after_soldering_back](https://github.com/user-attachments/assets/6be57772-8843-487d-a4f7-ff11a0c98619)




## Resouces

All the gbr & drl files can be found in the zip file [*here*](https://github.com/user-attachments/files/23944338/gbr.drl_files_PCB_GARDEN_BUDDY.zip),
and the ecad project files can be found [*here*](https://github.com/user-attachments/files/23466681/subsystem-all-project-ecad-files.egr304-RSC.zip).
