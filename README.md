# STEVAL-MKI109V3-ism330dhcx
development platform: STEVAL-MKI109V3;	sensor: ism330dhcx accelemeter and gyroscope

Use the MCU (stm32f401ve) on the development platform to control the sensor. 	Use I2C channel to communicate with the sensor, which include writing the FSM to the sensor, and reading the FIFO data from the sensor.	The code also include the function to store the data into the flash memory of stm32.

After generate C code of FSM from Unico-GUI, which provided by ST, wirte the FSM c code to the sensor by using 
