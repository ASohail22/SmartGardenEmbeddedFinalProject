# SmartGardenEmbeddedFinalProject

This project requires the use of 2 sensors and an LCD to communicate data over to the ThingSpeak cloud. The specific parts utilized were the YL-69 Sensor and HC-38 Module for the soil moisture sensor,  the SHT40-AD1B-R3 for the temperature and humidity sensor, and the NHD-0216AW-IB3 for the LCD. Additionally to these components are three LEDs (red, green, and yellow) and the ESP8266 WRL-17146 wifi module. These additional components are to give additional data about the temperature from the use of the LEDs and to communicate the data to the “ThingSpeak” from the wifi module. These parts were implemented through the creation of a PCB that holds all of the components and the use of the MSP430 microcontroller.

In the end, the internal temperature sensor was utilized instead of the I2C sensor and the data was not communicated over ThingSpeak.
