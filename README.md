# Motion detection-MKI109V3-ism330dhcx
development platform: STEVAL-MKI109V3

accelemeter and gyroscope sensor: ism330dhcx

After generate C code of FSM from Unico-GUI, use the MCU (stm32f401ve) on the development platform to control the sensor: setup the sensor and get the data of the sensor.

Before control the sensor, the program set up some necessary selector in the motherborad.

The program include the function to write the C code of confirgured FSM to the sensor by using I2C. Then, the bottom_2 is used to control the process to get the data from the sensor. Every time push the bottom will start/stop the process to get the data. The process to get the data include read data from sensor by using I2C & write the data into flash.

Also there are two LEDs used, LED1 is on when read data, LED2 is on when the flash of MCU is full (flash memory end address is 0x0807 FFFF).  
