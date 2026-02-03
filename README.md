# Microwave_Oven_PICSIMLAB
This project demonstrates the design and implementation of a Microwave Oven Controller using a microcontroller. It simulates the working of a real microwave oven by providing different cooking modes and user interaction through a keypad and LCD display.

The system allows the user to select modes such as Micro, Grill, and Convection, set the cooking time, and start the operation. The status and selected options are displayed on a 16x2 Character LCD (CLCD). Timers and interrupts are used to manage time-based operations efficiently.

⚙️ Features

Multiple cooking modes: Micro, Grill, Convection

User input through Matrix Keypad

Real-time display using 16x2 CLCD

Timer-based cooking operation

Buzzer indication after cooking completion

Modular Embedded C code

🧰 Hardware Used

PIC16F877A Microcontroller

16x2 Character LCD (CLCD)

Matrix Keypad

Buzzer

Power Supply

Proteus / MPLAB X for simulation

💻 Software & Tools

MPLAB X IDE

XC8 Compiler

Embedded C

🔄 Working Principle

The user selects a cooking mode using the keypad.

The cooking time is set through keypad input.

The microcontroller starts the timer based on the selected mode.

The remaining time and mode are displayed on the LCD.

After the timer expires, a buzzer is activated indicating completion of the process.

📂 Project Structure

main.c – Main application logic

clcd.c / clcd.h – LCD driver

matrix_keypad.c / matrix_keypad.h – Keypad driver

timers.c / timers.h – Timer configuration

micro_oven_def.h – Project definitions

🚀 Applications

Home appliance control systems

Embedded systems learning project

Real-time timer-based applications
