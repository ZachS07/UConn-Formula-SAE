# UART-to-CAN Converter Design

## Initial Design Schematic

![UART-to-CAN Converter Schematic](UART_CAN_Schematic.png)

As part of the LV battery system development, I designed an initial UART-to-CAN converter to support communication between the BMS and the vehicle's CAN bus.

The design uses an STM32F103 microcontroller to receive UART data and interface with a CAN transceiver. The schematic also includes CANH/CANL connections, power and decoupling circuitry, and an SWD header for programming and debugging the STM32.

This schematic shows the design at an early stage. Some of the connector pins, BMS connections, and component values are still unspecified because we have not finalized all of the communication and hardware requirements yet.
