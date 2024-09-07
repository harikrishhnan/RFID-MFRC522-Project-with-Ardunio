# RFID MFRC522 Project with Arduino

## Overview
This project demonstrates how to use the **RFID MFRC522 module** with an **Arduino** to read and process RFID tags. It serves as an entry-level guide to working with RFID technology and microcontrollers for identification and access control systems.

## Features
- Read RFID tags using the MFRC522 module.
- Interface RFID with Arduino for real-time tag processing.
- Display tag data on a connected serial monitor.
- Provide a foundation for building secure access control systems.

## Components Used
- **Arduino Uno/Nano/MEGA** (any compatible Arduino board)
- **RFID MFRC522 module**
- **Jumper wires**
- **Breadboard**
- **Power supply**
- **RFID tags/cards**

## Prerequisites
1. Basic understanding of Arduino programming.
2. Install the **MFRC522 library** for Arduino:
   - Open Arduino IDE.
   - Go to **Sketch > Include Library > Manage Libraries**.
   - Search for **MFRC522** and install it.

## Circuit Diagram
Connect the **MFRC522** module to the Arduino as follows:

| MFRC522 Pin | Arduino Pin |
|-------------|-------------|
| SDA         | Pin 10      |
| SCK         | Pin 13      |
| MOSI        | Pin 11      |
| MISO        | Pin 12      |
| IRQ         | Not Connected|
| GND         | GND         |
| RST         | Pin 9       |
| 3.3V        | 3.3V        |

## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/harikrishhnan/RFID-MFRC522-Project-with-Ardunio.git
