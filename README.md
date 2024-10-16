# First-RTOS-Program-Task

This project is an implementation of a system based on STM32 that measures voltage using the ADC (Analog-to-Digital Converter) and displays notifications on the terminal when a button is pressed and LED is on.

## Description

This project provides a practical example of how to:
- Measure voltage using the STM32's ADC.
- Use GPIO to control a LED.
- Display voltage readings on a terminal using UART.
- Monitor a physical button to toggle the LED and display notifications.

## Task Workflow
[Diagram Task](https://drive.google.com/uc?export=view&id=1yuxE9chiDTIBMvnxqW10Z6yE5SgrUVri)

The system includes the following tasks:

1. **Initialization**:
   - Configure GPIO, ADC, and UART peripherals.
   
2. **Task ADC**:
   - Reads the voltage values from the ADC input.
   
3. **Task LED**:
   - Monitors and controls the state of the LED (on/off).
   
4. **Task UART**:
   - Displays menu and ADC voltage readings on the terminal.
   - Displays state of the button and LED.
   
5. **Task Button**:
   - Read button state (pressed or not) and set LED state (ON or OFF) based on button state.

## Hardware Used
[Photo](https://drive.google.com/uc?export=view&id=1vKf5dllwltwZLlrbhl3RC-ONb9Geyj1T)
- STM32 Microcontroller
- Physical button
- LED
- Potentiometer
- ST-Link Mini Debugger
- USB to TTL UART

## Demo Video

Watch the [demo video](https://drive.google.com/uc?export=view&id=1K8y1CNX6x7BClinXpqIBEwHeo5qAbfXO) showcasing the project in action.
