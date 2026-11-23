# Solid-State Power Distribution Module (SSPDM)

This project involves designing a Solid-State Power Distribution Module for our Formula SAE EV.

Right now, the car uses traditional fuses to protect its low-voltage electronics. The goal is to replace these with electronic switches that can shut off power when something goes wrong, while also allowing us to monitor current and identify faults more easily.

The PDM will have six separate output channels controlled by an STM32 microcontroller. We're using PROFET smart switches to control power to each channel and plan to send current measurements and fault information through CAN.

So far, we've been working on the initial schematics in Altium, including the microcontroller, power regulation, CAN communication, and PROFET switching circuits.

The next steps include finalizing the schematics, designing the PCB, programming the microcontroller, and testing the system.

## Project Documentation

- [MCU, CAN, and Power Regulation Schematics](Power_Schematics.md)
- [PROFET Switching Schematics](PROFET_Schematics.md)
