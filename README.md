ATAPIHat
=============================

![PCB](ATAPIHat.png)

#### Overview

#### Rev. A Errata
Reset is wrong, is hardpulled to ground. Solution: connect to GPIO17.   
Chip select is non-ideal (solder jumper?)  
Selectable 5V/3.3V on Pin 20 required  
IDE Reset line should be connected to LED7 aka pin 28 of U4  
Signal integrity issues, paralell termination resistors (maybe 120 Ohms) and series termination would be ideal.  

#### Additional info

[Firmware](https://github.com/Manawyrm/ATAPIHat-Firmware)  
[Schematic](https://github.com/Manawyrm/ATAPIHat/blob/master/ATAPIHat.pdf)  
