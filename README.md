In this project implemented a lighting control system.
The device consists of a chipkit WiFire board with PIC32MZ microcontroller, Bluetooth module HC-05, light sensor BH1750.
For demostration using the LD1 LED on the board. 
Control is carried out using the Android application on the smartphone via Bluetooth.
The screen displays the value of the illumination level, which is measured by the sensor. 
There are 2 modes of control: manual and smart. 
In manual mode, you can turn the lamp on and off with the buttons.
To activate smart mode, you must press the "Smart Mode" button. In smart mode, the lamp is on if the illumination level is less than 20 lux, otherwise the lamp is turned off.



For programming was used the Arduino IDE (1.8.8). To configure the IDE, you need to follow the instructions in the guides: 

https://www.youtube.com/watch?v=DOEdmc57FVU 
https://chipkit.net/wiki/index.php?title=ChipKIT_core. 

You also need to download and connect the libraries: math.h, Wire.h, WString.h, BH1750.h