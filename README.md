Laird LoRa/Bluetooth Low Energy Module breakout for RM1xx modules
=================================================================

This breakout is used to hold Lairdtech Lora/BLE [module][1] RM186 (868MHz) or RM191 (915MHz) and contains the followings features
- I2C Pullups placement
- CR2540 or LIR2450 battery holder
- Resitor divider to measure battery voltage
- On board 3V3 regulator (so Lipo can be used)
- JST2 Lipo connector
- FTDI connector
- Prog/Debug connector footprint
- Breadboard friendly

Boards have been ordered at PCBs.io.    

**Boards are not tested yet, use at your own risk.**

Detailed Description
====================

Look at the schematics for more informations.

- Place R6 and R7 divider only if you need to measure Vbat from Analog SIO04
- Place R3 and R4 only if you whan to use I2C devices


### Schematic  
![schematic](https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Breakout-sch.png)  

### Boards  
<img src="https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Breakout-top.png" alt="Top" width="40%" height="40%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Breakout-bot.png" alt="Bottom" width="40%" height="40%">

You can order the PCB of this board at [PCBs.io][3] if you do so, PCBs.io give me little discount that allow me to buy some new created boards.

### Assembled boards

To Do.

##License

You can do whatever you like with this design.

##Misc
See news and other projects on my [blog][2] 

[1]: http://www.lairdtech.com/products/rm1xx-lora-modules
[2]: https://hallard.me
[3]: https://PCBs.io/share/4Kwa4 

