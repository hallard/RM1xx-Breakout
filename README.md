Laird LoRa/Bluetooth Low Energy Module breakout for RM1xx modules
=================================================================

These breakout are used to hold Lairdtech Lora/BLE [module][1] RM186 (868MHz) or RM191 (915MHz). There are 2 versions, one minimal to place on veroboard kind and one other the be placed on breadboard
They contains the following features

- Full version
  - I2C Pullups placement
  - CR2540 or LIR2450 battery holder
  - Resistor divider to measure battery voltage using analog pin
  - On board 3V3 regulator (so Lipo can be used)
  - JST2 Lipo connector
  - FTDI connector
  - Prog/Debug connector footprint
  - Breadboard friendly

- Minimal version
  - I2C Pullups placement
  - Veroboard friendly

Boards have been ordered at PCBs.io and have been tested and they are working fine.

Detailed Description
====================

Look at the schematics for more informations.

- Full version 
  - Place R6 and R7 divider only if you need to measure Vbat from Analog SIO04
  - Place R3 and R4 only if you whan to use I2C devices

- Minimal version 
  - Place R1 and R2 only if you whan to use I2C devices


### Schematic 

**Full version**
Click to enlarge 
![schematic](https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Breakout-sch.png)  

**Minimal version**
Click to enlarge 
![schematic](https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Min-Breakout-sch.png)  


### Boards (Full Version)

**Top**    

<img src="https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Breakout-top.png" alt="Top">
    
**Bottom**    

<img src="https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Breakout-bot.png" alt="Bottom">

You can order the PCB of this board at [PCBs.io][3] if you do so, PCBs.io give me little discount that allow me to buy some new created boards.

### Boards (Minimal Version)

**Top**    

<img src="https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Min-Breakout-top.png" alt="Top">
    
**Bottom**    

<img src="https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Min-Breakout-bot.png" alt="Bottom">

You can order the PCB of this minimal breakout board at [PCBs.io][4] if you do so, PCBs.io give me little discount that allow me to buy some new created boards.

### Assembled boards

<img src="https://raw.githubusercontent.com/hallard/RM1xx-Breakout/master/pictures/RM1xx-Breakout-mounted.jpg" alt="assembled">


##License

You can do whatever you like with this design.

##Misc
See news and other projects on my [blog][2] 

[1]: http://www.lairdtech.com/products/rm1xx-lora-modules
[2]: https://hallard.me
[3]: https://PCBs.io/share/zeJ24 
[4]: https://PCBs.io/share/49GYW

