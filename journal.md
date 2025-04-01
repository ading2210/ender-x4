Made by: ading2210 // vk6
Repository link: https://github.com/ading2210/infill-printer
Total hours so far: 7

- [x] I have a 3D printer or will be getting one before March 21st

## 3/13/25 (2.5 hrs) - Research design goals and feasibility

I did these notes on a Google Doc originally, so here it is copy-pasted:

**Goals:**

* Reuse as many parts as possible from 2 stock Ender 3 printers   
* Quad extruder with independent hotends (IDEX or single toolhead?)  
* Under $250, used parts allowed  
* Entirely off the shelf components and printed parts  
* Maximize build volume 

**IDEX Design**

* Need 4 x axis motors and 4 belts  
* Total motor count – 4 x axis, 1 y axis, 4 extruder, 2 z axis (total: 11).   
  * 1 extra motor (Nema 17\) needed for x axis ($10)  
* Control boards (option 1):  
  * Main: BTT Octopus ($80)  
    * Used for x, y, z axis and bed heater  
  * Extra: 2x stock Creality v1.1.4 (or v4.2.7)  
    * Used for all 4 extruders, 4 hotend heaters  
* Control boards (option 2):  
  * Main: BTT SKR v1.4 ($30) \+ 5x TMC2209 ($20)  
    * Used for x, y axis and bed heater  
  * Extra: 2x stock Creality v1.1.4 (or v4.2.7)  
    * Used for all 4 extruders, z axis, 4 hotend heaters  
* Control boards (option 3):  
  * Main: BTT SKR Mini E3 v2 ($35)  
    * Used for x axis and bed heater  
  * Extra: 2x stock Creality v4.2.7   
    * Used for all 4 extruders, z axis y, axis, 4 hotend heaters  
* Extra cost: $35-$90

**Single Carriage Design**

* Only 1 x axis motor and belt  
* Total motor count – 1 x axis, 1 y axis, 4 extruder, 2 z axis (total: 7\)  
* Control boards:  
  * Main: BTT SKR Mini E3 v2 ($35)  
    * Used for x, y, z axis and bed heater  
  * Extra: 2x stock Creality v1.1.4  
    * Used for all 4 extruders, 4 hotend heaters  
* Extra cost: $35

**Attributes Common to Both Designs:**

* Ender 3 v2 Neo might be used instead because those are cheap on ebay  
  * Otherwise use the Ender v3 v1 because that one is open source  
* 2 power supplies (stock ones used)  
* 2 of the hotends and extruders need to be purchased  
  * [Creality Direct Drive Kit](https://www.amazon.com/Creality-Original-Extruder-Flexible-Filament/dp/B09NVWJYMT) x2 ($60)  
* Purchase 2 Ender 3 v1s used ($100 \- $120)  
* Main computer is Raspberry Pi 3 with Klipper  
* Dual X axis gantry, dual z axis motors  
* Keep a belt slinger design   
* Use stock rollers for x axis (linear rails if within budget)  
* Keep stock hotend   
* Keep stock motors  
* Direct drive