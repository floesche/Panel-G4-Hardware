---
title: Panel PCB
parent: Hardware
grand_parent: Generation 4
---

# Production files

The `.art` files are GERBER RS274X files.

The `Assembly.art` file contains the constraints for production. For example, the copper layers are as follows: `TOP`, `GND`, `LAYER_1`, `LAYER_2` `PWR`, `BOTTOM`. The files are generated 2020-08-12 from the Cadence design files, based on the "2017 V1" design. The drill file does not contain tool selection. 

* Assembly.art - Assembly instructions
* BOM V2.xlsx - Bill of Materials
* BOTTOM.art - Bottom Cu layer (Layer 6)
* GND.art - Ground Cu layer (Layer 2)
* LAYER_1.art - Logic Cu layer 1 (Layer 3)
* LAYER_2.art - Logic Cu layer 2 (Layer 4)
* LED Panel G4 V1, 03-26-2017-1-6.drl - drill file
* Pin1.txt - centroid placement for the pin 1 location of each component
* place_txt.txt - centroid placement file
* PWR.art - power Cu layer (Layer 5)
* README.mdown - this file
* SilkScreen_Top.art - Top silkscreen
* SolderMask_Bottom.art - bottom solder mask
* Soldermask_top.art - top solder mask
* TOP.art - top Cu Layer (Layer 1)