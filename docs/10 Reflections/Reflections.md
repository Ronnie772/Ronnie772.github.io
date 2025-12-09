---
title: Reflections
tags:
- tag1
- tag2
---


## Overview
The Reflections section summarizes the key insights gained throughout the development of the motor subsystem and the overall Garden Buddy project. It highlights what worked well and the lessons learned during the design, testing, and integration phases. By reflecting on both successes and setbacks, this section provides meaningful context for future improvements and offers guidance for teams who may build on this work in later iterations of the project.

## Lessons Learned

1.Document everything, at the end of each session of work make notes on what needs to be changed and updated in the digital documentation.

2.Start hardware–software co-development early, don’t wait for final hardware to start firmware logic. Even partial schematics or simulated signals can be enough to begin writing, testing, and refining control structures. When hardware finally arrives, the software is already stable.

3.Build subsystems within subsystems so they can be tested independently, designing each subsystem so that it can be verified in isolation before integrating. This prevents cascading problems and reduces debugging time dramatically.

4.Version-control everything, store KiCad files, code, PDFs, lab notes, and firmware versions in a systematic manner so that when it's time to integrate everything, it doesn't jumble up.

5.Label everything on the schematic with purpose, not just values for components.
Set up consistent meetings to make sure that everyone is on task and continuing to do the project properly.

## Recommendations for the future

1.Use simulation tools before wiring, like LTspice. Simulating power rails or PWM duty effects catches conceptual errors early.

2.Prioritize clarity in wire management.

3.Make sure that your subsystem meets the project requirements before even starting to create a schematic, so you don't have to redo work.
