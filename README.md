# MX_Alps_Hybrid
KiCad Libraries of keyboard switch footprints

![Footprint Image](https://raw.githubusercontent.com/ai03-2725/MX_Alps_Hybrid.pretty/master/Screenshots/Footprint.png)  

### Included Libraries
* **MX_Alps_Hybrid.pretty** - The original MX/Alps hybrid support footprints.  
	* FLIPPED - Reversed LED pads for overlapping switch footprints.
	* NoLED - No LED pads.
	* ReversedStabilizers - Stabilizer mirrored vertically (i.e. for bottom row).
* **MX_Only.pretty** - Only for Cherry MX and derivative clones.  
	* FLIPPED - Reversed LED pads for overlapping switch footprints.
	* NoLED - No LED pads.
	* ReversedStabilizers - Stabilizer mirrored vertically (i.e. for bottom row).
	* Hotswap - Kailh hotswap sockets.
* **ALPS_Only.pretty** - Only for alps SKCM/SKCL, SKBM/SKBL, and clones with same pin structure.  
	* LED - Specifically for Alps SKCL with in-switch indicators.
* **Kailh_Choc.pretty** - Only for Kailh Choc switches.  

### Features
 * Designed from scratch using official datasheets and accurate measurements
 * Various footprints for all occasions
 * Almost every switch size in existence
 * Topside soldermask to prevent solder overflow and improve appearance

### Upgrading
The library was overhauled on June 1st, 2019 due to its aging structure and contents.
* The schematic components were updated to work on the 50mil grid. You can replace the components; however, it will take a decent amount of work.
	* If you wish to do this, remove the old schematic library, re-add the new one, and replace the schematic components.
* The footprint library was divided into four distinct libraries. Remove the previous, re-add the libraries with the footprints you are using, then rebind the footprints in the schematic.  

### Request More Footprints
I'll be more than happy to make more custom footprints to fit your needs, time permitting.
Simply contact me via Discord @ai03#2725, or twitter @ai03_2725.

### Contributing
Feel free to create pull requests with more footprints. I only ask that they are of high quality, and that they are based on official dimensions, if possible.

![Schematic Image](https://raw.githubusercontent.com/ai03-2725/MX_Alps_Hybrid.pretty/master/Screenshots/Schematic.png) 
![Top render Image](https://raw.githubusercontent.com/ai03-2725/MX_Alps_Hybrid.pretty/master/Screenshots/Render-Topside.png)  
![Bottom render Image](https://raw.githubusercontent.com/ai03-2725/MX_Alps_Hybrid.pretty/master/Screenshots/Render-Bottomside.png)  
