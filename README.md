# Temperature-Probe-
This project uses a thermocouple probe to measure meat's internal temperature on a grill, displaying it on an OLED. It provides alerts for different doneness levels. The system includes linearization of the thermocouple's non-linear response, and features a graphic UI for output and buttons for user inputs.

Project Description:
The project involves measuring the internal temperature of meat on a grill using a thermocouple probe.
The measured temperature will be displayed on an OLED display.
The device will provide alerts indicating the level of "done-ness" of the meat.
Linearization of non-linear temperature sensors will be implemented.
A graphic user interface (UI) for output and buttons for inputs will be developed.

Software Used:
IAR Embedded Workbench for ARM (EWARM) is the Integrated Development Environment (IDE) used for coding and debugging.
STM32CubeMX from ST is used for configuring STM32 microcontroller peripherals.
YAT or any other terminal emulator will be used for serial communication.
Git is used for version control.
Open-source software for sound generation might be used.

Kit Contents:
Two ST microcontroller development boards are included.
Protoboard and wires for circuit prototyping are provided.
Various passive components such as resistors, capacitors, and thermistors.
Active components including diodes, transistors, and ICs such as op-amps and sensors.
Other devices like the thermocouple probe, display, microphone, and terminal block are provided.

Assumed Skills:
Basic understanding of the C programming language including declaring functions, variables, arrays, structures, unions, pointers.
Familiarity with keywords like typedef, #define, extern, #include.
Understanding the difference between "." and "->" in C.
Knowledge of file management in the IAR Embedded Workbench IDE.


Files in IAR Embedded Workbench IDE: average.h: Header file for averaging functions.

fonts.c: File for font handling.

KeyboardHoldRepeat.c and KeyboardHoldRepeat.h: Files related to keyboard input handling.

main.c and main.h: Main application files.

serial_user.c: File for serial communication.

ssd1306.c: File for controlling the SSD1306 OLED display.

stdint.h: Read-only file for standard integer types.

stm32g0xx_hal.c: HAL (Hardware Abstraction Layer) file for STM32G0xx series microcontrollers.

Various files related to HAL configuration, interrupt handling (stm32g0xx_hal_adc.h, stm32g0xx_hal_gpio.h, stm32g0xx_hal_i2c.c, stm32g0xx_hal_msp.c, stm32g0xx_it.c).

Files related to thermistor and thermocouple handling (Thermistor.c, Thermistor.h, Thermocouple.c, Thermocouple.h).

Files related to user experience management (ux_manager.c, ux_manager.h).
