# boxhot
<h4>A heated enclosed Core XY FDM 3d printer. It is a box that is hot -> boxhot. </h4>

![alt text](https://github.com/xKZx/boxhot/blob/main/a3.png?raw=true)

<h6>The design is a celebration to the fact that patents eventually do expire. </h6>

Quick overview
1. Single direct extruder, 300x300x450mm print volume;
2. Heated chamber;
3. Linear guideways;
5. All motors outside of the box (hot in there, motors like to be cool);
6. 3 Z-axis stepper motors = real bed leveling;
7. Uses mostly off the shelf components, laser cut SS panels and 3030 aluminium extrusions. Estimated cost ~850.- Eur using china sourced components. 

<h4>First prototype currently in progress.
BOM and assembly documentation will follow after initial prototype.</h4>

<h6>Design Criteria</h>

The idea was to build a 3d printer for engineering purpouses. To be able to print basic plastic materials as ABS, TPU, Nylon and ASA without any warping, cracking or other issues. 
After initial sketching I set certain details I wanted:
 - Heated chamber, powered by mains. Most thermoplastics need to be held at a certain temperaturee to print properly, but this technology was previously patented, so only hot beds and easy to print materials (PLA) were used as a temporary fix to the issue. Amazing results can be achieved with the cheapest printers nowadays, but it can be better. Powered by a 750w heater and insulated on 4 sides with 30mm mineral wool.
 - Motors outside heated zone, keeps them cool. This is common electronics engineering sense.
 - Safe against fire, this means a enclosure that is not flamable - I chose stainless steel as it is more readily available than fireproof sheets of plastic or other composite. Besides it is 10 less heat conductive than aluminium.
 - Thee Z axis for real leveling. Build platform level can cause several printing issues so a more complex and maintenace free system is better. The Z motors are sourced from a Prusa style printer with 500mm leadscrews integrated. The PEI covered BED is also heated with a 750w 220v silicone heater. 
 - Runs Marlin 2.0 on BTT GTR 1.0, but can be expanded with a RPi. GTR 1.0 has 6 motors that support the leveling feature just mentioned. 
 - Core XY belt system, some have found this to be one of the best belt design possible. My flavour uses two more untoothed pulleys on X axis to create a more smooth connection to the printhead as pulleys with low tooth count (20 in this case) can cause vibrations. Pulleys with no teeth in theory should improve this. 
 - The cost had to be bellow 1000.- Eur 
 - Bellows close the enclosure, allowing the head to keep cool and keeping the enclosure steamy. This increases the efficiency.
 - And most importantly it had to be easy to modify and maintain. The print head is removable and the entire Core XY assembly can be removed from the Z stage. 
 
