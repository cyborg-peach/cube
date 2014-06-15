# Cube

Cube enables experts across the world to grow plants for you out of your home or office.

## Supplies

To build a cube, you'll need the following supplies:
[Arduino Uno R3](https://www.sparkfun.com/products/11021)
[Hydroponic rock](http://www.amazon.com/Hydroton-Leca-Orchid-Hydroponic-Media/dp/B004IAM29K)
[Weather shield](https://www.sparkfun.com/products/12081)
[Stacking headers](https://www.sparkfun.com/products/11417)
[Hydroponics kit](http://www.amazon.com/Stealth-Hydroponics-DWC-Basic-Kit/dp/B005K2VKK2/)

## Setup

*  Solder the headers on the weather shield using [this guide](http://www.freetronics.com/pages/soldering-shield-headers)
*  Mount the weather shield on the Arduino Uno
*  Plug the Uno into your computer's USB port
*  Install dependencies and configure bash to support compiling arduino code using [this readme](https://github.com/sudar/Arduino-Makefile)
*  Clone this project to your local computer
*  Run **make** to compile the project
*  Run **make upload** to upload the code to the arduino
*  Run **make monitor** to see output from the arduino sensors
*  Once the arduino is working reading sensors property, assemble the hydroponic garden and mount the sensor to it