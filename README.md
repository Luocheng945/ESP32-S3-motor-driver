# ESP32-S3-motor-driver

![3D render of the ESP32-S3 motor driver board](images/esp32expansion(3Drender).png)

## Project Description

A custom 4-layer ESP32-S3 control board designed for robotic applications.

The board includes voltage conversion, two TI DRV8872DDAR motor drivers, servo control, and ESP32-S3 I/O expansion.

## Schematic

![Schematic](images/ESP32expansion(Schematic).png)

[View detailed schematic (PDF)](docs/ESP32S3_Vehicle_Control_Board_Schematic.pdf)

## Project Status

🟩 **First bring-up:** All voltage converters are outputting correct voltages, including 7.4V, 5V, and 3.3V. Two DC motors and one servo motor can be powered and driven by the board.

🧪 **Ongoing testing focus:** Motor stall testing.

## Manufacturing

The PCB was fabricated by JLCPCB, with all components sourced from DigiKey.

The board was fully assembled by hand, including 0603 components and SOT-583 packages.

Third-party footprints were modified where necessary to reduce fabrication cost.

## Application

![Actual image of the ESP32-S3 motor driver board](images/esp32expansion(actual).jpeg)

[GitHub Link](https://github.com/Luocheng945/WanHu)
