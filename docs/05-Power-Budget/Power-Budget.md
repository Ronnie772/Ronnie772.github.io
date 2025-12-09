---
title: Power Budget
---

## Overview
The power budget outlines the total electrical power required for the motor subsystem, It ensures the power supply can reliably support all operating conditions without overload or performance issues.

To confirm that the motor subsystem can be safely and reliably powered, each device is listed along with its operating voltage range and maximum current draw to ensure that the selected power sources and regulators can supply sufficient current with an added 25% safety margin.

Section A identifies all significant current-consuming components in the motor subsystem, including the LM7805T voltage regulator, the PIC18F57Q43 Curiosity Nano board, and the Pololu DC motor.

Section B then assigns each of these components to the +5V rail, allowing the calculator to verify that the LM7805T can support the total load without exceeding its current limits.

The subtotal current draw, combined with the safety margin, determines the total current required from the +5V regulator. Finally, the regulator’s output capability is compared against this requirement to confirm that it provides adequate current headroom. As shown in the image, the LM7805T regulator meets the demand, leaving remaining current available for safe operation.

<img width="1710" height="603" alt="image" src="https://github.com/user-attachments/assets/83fb27c0-9a33-4d68-8fbe-d8ca5c7a3567" />


<img width="1710" height="584" alt="image" src="https://github.com/user-attachments/assets/687fd895-5c0b-4541-af6e-6079db40e28f" />


## Conclusions
This power budget validates that the subsystem’s component selection and power architecture, ensuring consistent performance while protecting against overload conditions.  

## Resouces

The power budget as a PDF download is available [*here*](https://github.com/user-attachments/files/23171101/Power-budget-rsc.pdf), and a Microsoft Excel Sheet [*here*](https://github.com/user-attachments/files/23171109/Power_Budget.xlsx).


