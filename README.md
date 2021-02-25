# ZoRAM - Eight Megabyte Fast RAM Expansion for the Amiga 2000

This project is early in development. It may or may not work at this time.

I have always felt big box Amiga's should be used as intended. Expansion should be targeted to the expansion slots provided. This project aims to provde an 8 megabyte expansion option via the Zorro II bus of the Amiga 2000. Based on Liv's GottaGoFastRAM for 68000 DIP based Amigas. Due to the relative messiness of the  data and address line locations on the Zorro II connector, it was necessary to  change the connection points on the Xilinx. As such, the JED file for this project is specific to this project and cannot be interchanged with Liv's original.

![ZoRAM Image](ZoRAM.jpg)


# PCB Ordering and Assembly

I stuck with surface mount components for this project since the Xilinx CPLD and Samsung memory module are only available in SMD configurations. I normally try to avoid SMD for DIY projects, but if I already had to deal with those, might as well make the entire project SMD.

# Programming the CPLD

To be completed later.

# BOM

|Component|Location|QTY|Source|Part Number|
--- | --- | --- | --- | ---
4Mx16 DRAM| U6 | 1 | Ali Express | K4E641612D or GM71VS65163
XC9572XL-10VQ64C|U5|1|DigiKey|xxxx
AP2210N-3.3TRG1|U2|1|DigiKey|xxxx
74LVC245N|U3,U4|2|DigiKey|xxxx
Ferrite Bead|FB1|1|DigiKey|xxxx
0.1uF Ceramic Capacitor|C3-12|10|DigiKey|xxxx
4.7uF Ceramic Capacitor|C1|1|DigiKey|xxxx
10uF Ceramic Capacitor|C2|1|DigiKey|xxxx
6 Pin Male 2.54 Pitch Header (Optional)|J1|1|DigiKey|xxxx

# Revision History

V0.5 - Initial Commit
