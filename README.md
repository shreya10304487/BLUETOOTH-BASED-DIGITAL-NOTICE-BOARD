# Bluetooth-Based Digital Notice Board

A Bluetooth-enabled embedded systems project developed using the **LPC2129 ARM7 Microcontroller** to display scrolling messages on an LED dot matrix. Messages are transmitted wirelessly from a mobile device via the **HC-05 Bluetooth module**, verified using a passkey, stored in **AT24C256 EEPROM**, and continuously displayed on the notice board.

## ✨ Features

- Wireless message transmission via Bluetooth
- Passkey-based message authentication
- Scrolling text display on LED Dot Matrix
- EEPROM storage for message retention
- UART communication with HC-05 Bluetooth module
- I²C communication with AT24C256 EEPROM
- Displays **"Waiting for message"** when no valid message is stored
- Developed in Embedded C

## 🛠️ Tech Stack

- Embedded C
- LPC2129 (ARM7)
- Keil μVision
- Proteus
- Flash Magic

## 🔩 Simulation Components

- LPC2129 Microcontroller
- HC-05 Bluetooth Module
- AT24C256 EEPROM
- 8×8 LED Dot Matrix Displays
- 74HC164 Shift Register
- 74HC573 Latch
