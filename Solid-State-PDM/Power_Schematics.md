# MCU and Power Schematics

This schematic shows the main control and power circuitry for our Solid-State PDM.

We're using an STM32F103 microcontroller to control the PROFET switches, monitor the different output channels, and communicate with the rest of the car through CAN.

Since the microcontroller can't run directly off the car's battery voltage, we have a switching regulator that steps 24V down to 5V, followed by a linear regulator that brings it down to 3.3V for the STM32.

The schematic also includes a CAN transceiver for communication with the car, six status LEDs for the output channels, and a programming connector for the microcontroller.

There's also a crystal oscillator for the microcontroller's clock and a reset circuit.

This is still part of the initial design, so some components and connections may change as we continue working on the PDM.

## Schematic

![MCU and Power Schematics](Power%20Schematics.png)

[Back to PDM Overview](README.md)
