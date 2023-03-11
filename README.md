# SplitKB Aurora Corne Vial
 Unofficial Vial firmware port of the SplitKB Auroa Corne keyboard
 
![image](https://user-images.githubusercontent.com/64993772/224502364-e023e1b4-0a95-4150-a4d7-249d79b3637b.png)

This repository contains both a readymade .UF2 for use in RP2040 based controllers, and the files to compile your own firmware. Just transfer the keyboards folder to your Vial repository and edit whatever you feel like modifying and compile.

I compiled the .UF2 by running ```make splitkb/aurora/corne:vial:CONVERT_TO=promicro_rp2040```

If you want to compile a regular AtMega32 firmware hex, you will need to modify the ```rules.mk``` file or mess around with other files. 
