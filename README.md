## Adafruit BNO055 + BMP280 BFF Add-On for QT Py PCB

<a href="http://www.adafruit.com/products/5937"><img src="assets/5937.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit BNO055 + BMP280 BFF Add-On for QT Py. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5937

### Description

Our QT Py boards are a great way to make very small microcontroller projects that pack a ton of power - and now we have a way for you to turn many QT Py boards into powerful 9 degree-of-freedom (9DoF) motion plus pressure/altitude sensing projects that are super small!

We call this the Adafruit BNO055 + BMP280 BFF—a "Best Friend Forever." When you were a kid, you may have learned about the "buddy" system; well, this product is kind of like that! It's a board that will watch your QT Py's back and give it more capabilities.

This PCB is designed to fit onto the back of any QT Py or Xiao board. It can be soldered into place or made removable using pin and socket headers.

Rather than spending weeks or months fiddling with algorithms of varying accuracy and complexity, you can have meaningful sensor data in minutes thanks to the BNO055. This smart 9-DOF sensor does the sensor fusion all on its own!  You can read the data right over I2C and Bob's yer uncle.

The BNO055 can output the following sensor data:

* Absolute Orientation (Euler Vector, 100Hz) Three axis orientation data based on a 360° sphere
* Absolute Orientation (Quaternion, 100Hz) Four point quaternion output for more accurate data manipulation
* Angular Velocity Vector (100Hz) Three axis of 'rotation speed' in rad/s
* Acceleration Vector (100Hz) Three axis of acceleration (gravity + linear motion) in m/s^2
* Magnetic Field Strength Vector (20Hz) Three axis of magnetic field sensing in micro Tesla (uT)
* Linear Acceleration Vector (100Hz) Three axis of linear acceleration data (acceleration minus gravity) in m/s^2
* Gravity Vector (100Hz) Three axis of gravitational acceleration (minus any movement) in m/s^2
* Temperature (1Hz) Ambient temperature in degrees celsius

The only thing it doesn't have is barometric pressure, which can be used for altitude calculations. Aha, that's why there's also a BMP280 sensor on board. This precision sensor from Bosch is the best low-cost, precision sensing solution for measuring barometric pressure with ±1 hPa absolute accuracy, and temperature with ±1.0°C accuracy. Because pressure changes with altitude and the pressure measurements are so good, you can also use it as an altimeter with  ±1 meter accuracy.

Usage for the BFF is simple is simple, because both the BNO and BMP talk over I2C - so you'll just use the SDA/SCL pins. Note that some QT Py boards with a Stemma QT port have two I2C ports, so make sure you are using the port that's on the SDA/SCL pins, not the QT port! There's optional Interrupt/Reset pins for the BNO055 if you want more advanced control, and each sensor also has address-changing jumpers in case you want to switch from the default addresses of BMP280 @ 0x76 and BNO055 @ 0x38.

If you'd like, you can solder the BFF directly on the back of your Xiao/QT Py or use the included header to solder each side to your QT Py to make a sandwich. You can also pick up an Itsy Bitsy short female header kit to make it removable but compact; you'll need to trim the headers to 7 pins long.

QT Py is not included! 

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
