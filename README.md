# Arduino PCB Exposure Unit Controller

## Project Description

This project is an Arduino-based controller for a **UV exposure unit used in PCB (Printed Circuit Board) fabrication**.  
The program is designed to be **uploaded to an ATmega328P microcontroller on the PCB of the exposure unit**.  
It automates the exposure process by controlling UV lamps and timing the exposure duration to ensure consistent and reliable results when producing photoresist-based PCBs.  

The goal of the project is to provide a simple, reliable, and affordable solution for hobbyists and makers who want to build their own UV exposure box for PCB manufacturing.

## Features

- Control of UV lamps for PCB photoresist exposure  
- Configurable exposure time  
- Simple user interface (encoder with button, OLED display)  
- Compatible with standard Arduino boards (ATmega328P)  
- Uses well-known open-source libraries (Adafruit and others)  

## Installation

1. Clone or download this repository.  
2. Open the sketch (`.ino` file) in the Arduino IDE.  
3. Install the required libraries (copies are included in the repository for convenience).  
4. Upload the sketch to the **ATmega328P on the PCB (via ICSP interface)**.  
5. Connect the hardware according to the provided schematic.  

## Usage

1. Place the PCB inside your UV exposure box.  
2. Set the desired exposure time.  
3. Start the process and let the Arduino control the UV lamps.  
4. Once the timer finishes, the lamps will automatically switch off.  

## Hardware Documentation

Detailed documentation is included in this repository (in Slovak):  

- **Schematic diagram** of the circuit  
- **PCB layout**  
- **Detailed description of the timer hardware** 

Please refer to the files in the repository for complete hardware instructions.

## Licensing

This project is licensed under the MIT License.  
Copyright (c) 2025 Martin Janček  
See the [LICENSE](./license.txt) file for details.

### Third-Party Libraries

This project includes external libraries that are distributed together with the sketch:

- Adafruit libraries licensed under the **MIT License** and **BSD License** 
- Other libraries licensed under the **MIT License** 

Each library retains its original license. Copies of their license texts are included in the respective library folders (`LICENSE` or `LICENSE.txt` files).

### Summary

- The sketch and original code in this repository: **MIT License** (Martin Janček, 2025).  
- Third-party libraries: remain under their original **MIT** or **BSD** licenses.  
- You are free to use, modify, and distribute this project, provided you respect the included license terms.
