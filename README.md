ATAPIHat
=============================

![PCB](ATAPIHat.png)

#### Overview

Replaced by https://github.com/Manawyrm/ATAPIHat-SMI  
Directly connected to the GPIOs, much higher speeds.   

**Don't manufacture this board (in either Rev.A or Rev.B).**  
This design isn't optimal at all. 

#### Rev. A Errata
Reset is wrong, is hardpulled to ground. Solution: connect to GPIO17.   
Chip select is non-ideal (solder jumper?)  
Selectable 5V/3.3V on Pin 20 required  
IDE Reset line should be connected to LED7 aka pin 28 of U4  
Signal integrity issues, paralell termination resistors (maybe 120 Ohms) and series termination would be ideal.  

#### Additional info

[Kernel driver](https://github.com/Manawyrm/pata-gpio)  
[Schematic](https://github.com/Manawyrm/ATAPIHat/blob/master/ATAPIHat.pdf)  
