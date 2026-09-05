# RCRoverV1

This is a modular rover platform built around an Arduino Uno R3. My goal is to create a small 4WD rover that can sense its environment, be driven remotely, and be built on with improvements (i.e. more sensors, better control, app integration, etc.) This is my second ever engineering project, so I'm excited to continue developing my skills!

Features/parts for version 1:
- 4 wheel drive chassis (4WD) for better control
- Arduino Uno R3 as the main microcontroller
- Detects obstacles using an ultrasonic sensor
- Wireless remote control using one joystick and a radio module
- Status indication using LEDs

## Render(s)

<img width="1420" height="632" alt="carmodelv1" src="https://github.com/user-attachments/assets/f86e8f0b-c8e4-4aea-a521-0932f16da91f" />

<img width="1008" height="632" alt="remotecontrollerv1" src="https://github.com/user-attachments/assets/ed2c1b6f-dc89-4ece-8f5a-ab7d92f53b53" />

## Wiring Diagram(s)

<img width="997" height="727" alt="Screenshot 2026-08-21 212820" src="https://github.com/user-attachments/assets/0082b97e-2f16-42cb-b3f3-fa618ede7a95" />

## CAD

The CAD for this project is split into two main models: the rover and the remote controller.

### Rover

The rover is designed as a 4WD platform. The CAD model includes the chassis and the components needed to make up the physical rover, including the wheels, motors, electronics, and other mounted components.

The rover CAD files can be found in the [CAD](CAD/) folder.

### Remote Controller

The remote controller is modeled separately from the rover. It includes the joystick and NRF24L01 radio module used to control the rover wirelessly.

The remote controller CAD files can also be found in the [CAD](CAD/) folder.

These models were created to plan the physical layout of the project and make sure that the different components can fit together correctly.

## Schematic

The schematic for this project was designed using KiCad. The KiCad files can be found in the [Electronics](Electronics/) folder.

The schematic documents the electrical connections between the different components of the rover and remote controller.

## Firmware

The firmware for the rover and remote controller is currently in development.

The rover firmware will run on an Arduino Uno R3 and will handle motor control, ultrasonic obstacle detection, wireless communication, and LED status indication.

The remote controller firmware will read the joystick input and send the corresponding control commands to the rover using the NRF24L01 radio module.

I plan to test and finalize the firmware once I have the physical hardware assembled so that I can properly test the code with the actual electronics.

The firmware files will be added to the [Firmware](Firmware/) folder as development continues.

## Bill of Materials

The [BOM.csv](BOM.csv) file contains the bill of materials for the project, including the components needed to build the rover and its electronics.

## Project Structure

The repository is organized into separate folders for the different parts of the project:

CAD/
    Rover and remote controller CAD files

Electronics/
    KiCad schematic and PCB files

Firmware/
    Firmware for the rover and remote controller

images/
    Project renders and diagrams

BOM.csv
    Bill of materials

README.md
    Project documentation

## Credits

This was made during Hack Club's Stardance YSWS. Thanks Hack Club!

Free GrabCAD designs used:

- [TT Gearbox Motor](https://grabcad.com/library/one-way-single-axis-tt-gear-box-motor-detail-model-1)
- [Wheel D65x25](https://grabcad.com/library/wheel-d65x25-1)
- [Arduino UNO R3](https://grabcad.com/library/arduino-uno-r3-1)
- [DRV8833 Dual H-Bridge Motor Driver](https://grabcad.com/library/drv8833-dual-h-bridge-motor-driver-doble-puente-h-1)
- [HC-SR04 Ultrasonic Sensor](https://grabcad.com/library/hc-sr04-ultra-sonic-sensor-for-arduino-1)
- [MPU6050 Accelerometer Module](https://grabcad.com/library/mpu6050-accelerometer-module-1)
- [M4 30mm standoff](https://grabcad.com/library/standoff-m4-30mm-1)
- [M4 socket head cap](https://grabcad.com/library/m4-socket-head-cap-screw-library-m4x4-m4x60-1/details?folder_id=14243896)
- [NRF24L01 Radio Module](https://grabcad.com/library/wireless-radio-transmitter-and-receiver-nrf24l01-1)
- [Joystick Module](https://grabcad.com/library/arduino-joystick-module-1)
- [Arduino Nano](https://grabcad.com/library/arduino-nano--1)
