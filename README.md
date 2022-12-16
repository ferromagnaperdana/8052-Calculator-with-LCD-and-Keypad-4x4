# 8052-Calculator-with-LCD-and-Keypad-4x4

This repo is containing my 8052 Calculator with LCD and Keypad 4x4 Final Project for Microprocessor System Lecture. 
This interfacing circuit is using ATS89S52-24PU for the microcontroller and running at 16 MHz clock speed from crystal oscillator using 33pF ceramic caps.
Keypad 4x4 is used for input device via PORT1 (Column) and PORT3 (Row).
LCD 16x2 is used for output device and connected to 8052 via PORT2 for data pins and PORT0 for command pins.
This minimum system circuit can also be used for general purpose via breakout port pins, 6-pin SPI programming port, and 10-pin USBASP programming port.
There is also 5V power rail and GND from 7805 LDO regulator that can supply up to 1A of current (from the datasheet).
