# LIS2DH

> Arduino device driver for communicating with LIS2DH accelerometer over I2C

![LIS2DH datasheet (PDF)](http://www.st.com/web/en/resource/technical/document/datasheet/DM00042751.pdf)

## Important:
Please note that this library is WIP, and all credit to the original author of this code.
I only added extra support for STM32Duino.

## Installation

Requires different Arduino Libraries depending on how you wish to interface with the chip.

* Requires [Wire.h](http://arduino.cc/en/reference/wire) for I2C support.

Download the repo as a zip file and install throught the Arduino IDE and select:

Sketch -> Import Library -> Add Library

Make sure that if you are installing updates that you remove any pre-existing libraries called "LIS2DH".

## Wiring Diagram

![LIS2DH wiring diagram](docs/LIS2DH.png)

I2C lines: SDA and SCL

