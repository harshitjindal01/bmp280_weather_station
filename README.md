# bmp280_weather_station
this project shows how to connect bmp280 with esp8266 or nodeMCU  and creating a weather station
The BME280 I2C interface uses the following pins:
1. VCC: 1.71V to 3.6V
2. GND: Connect to GND
3. SCL: serial clock (SCK)
4. SDA: Serial data (SDI)
5. CSB: Must be connected to VDDIO to select I2C interface.
6. SDO: The I2C address decides the pin. If SDO connects to GND(0), the address is 0x76, if it connects to VDDIO(1), the address is 0x77.
In this module, we have connected it to VDDIO, so the address should be 0x77.
