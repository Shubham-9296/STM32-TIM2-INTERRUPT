STM32F407 Timer2 Interrupt

Overview

This project demonstrates Timer 2 (TIM2) Interrupt implementation on the STM32F407 Discovery Board using Embedded C, STM32CubeIDE, and the STM32 HAL Library. TIM2 is configured to generate periodic interrupts, where an LED is toggled inside the interrupt callback function.

Hardware Required

STM32F407 Discovery Board
On-board LED (or External LED with 220Ω Resistor)
USB Cable
Software Used

STM32CubeIDE
Embedded C
STM32 HAL Library
Features

TIM2 periodic interrupt generation
Interrupt handling using HAL callback function
LED toggling on every timer interrupt
Configured using STM32CubeMX
HAL Library implementation
Hardware Connections

STM32F407 Discovery Board
On-board LED (No external hardware required)
If using an external LED, connect it to the configured GPIO pin through a 220Ω resistor.
Project Structure

Core/
├── Inc/
│   └── main.h
├── Src/
│   └── main.c
How to Run

Open the project in STM32CubeIDE.
Build the project.
Connect the STM32F407 Discovery Board.
Flash the program to the board.
Observe the LED toggling periodically through the TIM2 interrupt.
Technologies Used

Embedded C
STM32 HAL Library
STM32F407 Discovery Board
Timer 2 (TIM2)
Interrupts
GPIO
