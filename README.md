# Boogie
Carbon/HEPA filter and sheet cooling in a tiny package!

![boogie](https://github.com/user-attachments/assets/ebb13ccf-2c6f-40a4-a78b-2cd0d06f4a7f)

It started as a dream... In my tiny printer, I wanted filtration and sheet cooling.
Using parts from other abandoned dreams and amateur but slowly improving CAD skills, this monstrosity was borne into the world.
3628 fans do the work and an MG90s servo makes the fans boogie!
Best of all, no need to disassemble your painstakingly squared frame, as I've created an M2 drop in nut holder to secure it all.

Enjoy the Boogie!

<br/><br/>

**A Few Notes:**
* Hex-zero bumps out the panels 3mm from a stock v0. This extra space is necessary for the fan rotation.
* I use SlideSwipe for my bed probe. I have not tested this with ZeroClick.
* I'm using the standard DragonBurner (not the Hex-Zero varient which I believe is lifted a few mm).
* Extreme left tilting of bed will likely cause some contact between bed and Boogie.
* When in fan mode, you'll have to limit the low end of x to about -5 or maybe -4 to prevent nozzle from colliding.
    * Can either limit this in config, or can make sure that all activities involving this area (maybe bed probing etc) are done prior to engaging fan mode.

<br/><br/>

**Bill of Materials (BOM)**
| Qty | Item | Notes |
| --- | --- | --- |
| 8 | 3x6 magnets |
| 12 | M2 nuts |
| 2 | M2x4 SHCS | To secure the servo horn. Can likely use 6mm if you use a spacer |
| 4 | M2x6 SHCS | To secure bottom mounts to frame |
| 6 | M2x8 SHCS | To secure top mounts to frame and servo to top rear mount |
| 1 | M5x10 BHCS | For the front mount |
| 8 | M3x35 BHCS | 32-33mm would be better, but I've got no bolt cutters |
| 8 | M3 nuts | For use as spacer, no need if able to acquire shorter screws |
| 8 | M3x5x4 heat set inserts | For the fan mount to secure fans |
| 1 | MR85zz bearing | Press fit into the fan mount. The M5 screw from front mount goes through here |
| 1 | MG90s servo with horn |
| 2 | 36mm x 28 mm fans | I'm using Delta FFB03612EHNYCL |
| 1 | Robot Vacuum Filter | Mine measure 130mm long x 40mm wide x 8mm tall which I've cut to length |
| ~80mm | 6mm wide x 1mm thick foam tape | Goes on the rear of filter (left on the photo) to improve fan seal to filter |
| Misc | Wiring, possibly a buck converter depending on your setup |

<br/><br/>
<br/><br/>
This work is licensed under a <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/" rel="nofollow">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>



