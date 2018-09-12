# Zio-Qwiic-Air-Pressure-Sensor-BMP280

Description

This little board features a high precision BMP280 Barometric Pressure and Altitude Sensor by Bosch. The sensor is not only capable of sensing pressure and altitude but it also environmental temperature, almost all the data you need around atmospheric conditions.

The sensor is one of the best low-cost solutions when it comes to take precise environmental data. The barometric pressure has a ±1.0 hPa absolute accuracy, on pressures from 200 hPa to 11hPa. Temperature measurements are pretty accurate also, with a ±1.0°C accuracy on temperatures between -40 and 85°C.

As the altitude increases, the atmospheric pressure decreases - and due to the sensor high accuracy on taking pressure measurements - the altitude can also be calculated. With a  ±1 meter precision on altitude sensing. 

Great sensor right? As a member of our Qwiic family, the board incorporates the Qwiic connector for easy wiring to use I2C interface. But this great little sensor can use either I2C or SPI so we made it pretty accessible to switch to SPI. Simply solder the header pins provided if you want to go for it!


Specification

    Operation Voltage: 3.3V
    Current Consumption: 2.7μA
    Barometric Pressure Measure
        Range: 300 – 1100 hPa
        Accuracy: ±1.0 hPa
    Temperature Measurement
        Range: -40 to 85
        Accuracy: ±1
    Interface: I2C and SPI
    Port: I2C (selectable address at 0x77(default) and 0x76)
    Dimensions: 16.5mm x 25.3mm
    Weight: 1.4g


Links

For testing code, we recommend use adafruit's BMP280 library, check the link here: https://github.com/adafruit/Adafruit_BMP280_Library

BMP280 Datasheet: https://cdn-shop.adafruit.com/datasheets/BST-BMP280-DS001-11.pdf
