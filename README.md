# The Data Pecker - a DB High-Res clone
The Data Pecker is a 100% compatible clone of the DB High-Res graphics board for PET/CBM 8000 series computers from 1982.
It implements all the features, with the option to build a 62256-based RAM-board instead of the original one using eight 6116.
Most of the components are readily available. Chips not available from Mouser or Digikey can still be purchased from a variety of sources in China. 

![Data Pecker render](https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_mainboard/images/dph_mainboard_render.png)

[Schematic](https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_mainboard/dph_mainboard.pdf "Schematic")  

[Bill of Materials](https://htmlpreview.github.io/?https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_mainboard/bom/dph_mainboard_bom.html "Bill of Materials")

[Wire connections](https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_mainboard/dph_mainboard_connections.pdf "Wire connections" )
## The original RAM Board
The is the true-to-the-original version of the RAM board containing eight 6116 SRAM ICs.

![Original RAM Board render](https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_ram/images/dph_ram_render.png)

[Schematic](https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_ram/dph_ram.pdf "Schematic")  

[Bill of Materials](https://htmlpreview.github.io/?https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_ram/bom/dph_ram_bom.html "Bill of Materials")

## The simplified RAM Board
This version replaces the old SRAM chips with a more modern 62256.

![Simplified RAM Board render](https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_ram_optimized/images/dph_ram_optimized_render.png)

[Schematic](https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_ram_optimized/dph_ram_optimized.pdf "Schematic")  

[Bill of Materials](https://htmlpreview.github.io/?https://github.com/InsaneDruid/Data-Pecker/blob/main/dph_ram_optimized/bom/dph_ram_optimized_bom.html "Bill of Materials")

## The Firmware
There are several ways to get both the programmed 2332A	ROM and TBP18s030 PROM	
chips for the Low Speed Graphik. One is to use U29 and U11 from a original HSG. 
This works well and is especially interesting for those seeking to replace a broken original HSG pcb.

The other possibility is to program a 2532 EPROM replacing U29 and a 18S030 PROM (or compatible, like 82S123, 27S19, 6331, 74S288, 7603a)
replacing U11. The firmware needed for flashing can be found on the web. The 18S030 can also be replaced by a GAL.



## The License
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License.  
See https://creativecommons.org/licenses/by-sa/4.0/.

## The Credits
This work would not have been possible without the help from a bunch of amazing people from [VzEkC e. V. forums](https://forum.classic-computing.de/forum/ "forum.classic-computing.de"). Many thanks go out to:

* *Toast_r* - for providing reference images and ohming out the hidden traces
