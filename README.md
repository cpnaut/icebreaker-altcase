# icebreaker-altcase
An alternative case for the [iCEBreaker FPGA](https://www.crowdsupply.com/1bitsquared/icebreaker-fpga) by [@esden](https://github.com/esden) based on [@pimdegroot](https://github.com/pimdegroot)'s design.

![Top](/v1.0b/ICE_Top_2.jpg)
![Bottom](/v1.0b/ICE_Bottom_2.jpg)

# Changes v1.0a
- Converted all mesh geometry to a set of polylines and a polysurface NURBS model.
- Added a gap in the top part for the Creset header.
- Added additional 2mm rim height on the top part.
- Added additional 1mm rim height on the bottom part.
- Removed redundant geometry on the bottom of the top part due to increased clearance.
- Added fillets in various corners to remove sharp edges.
- Added a 1BitSquared logo on the top part.
- Added a diagonal hatch pattern on the top and bottom parts.
- Added 0.3 mm clearance for the for M3 nuts on the bottom.
- Added supports on the bottom that need to be removed after printing. 
- Corrected several errors.

# Changes v1.0b
- Removed holes on the top part.
- Added four small cylindrical extrusions on the top that fit on the bottom
- Removed nut spaces and bolt holes on the bottom.
- Added four holes on the inside of the bottom to fit the extrusions.
- extended diagonal hatch pattern on both parts of the case.  

![Diff](/v1.0b/ICE_Diff_2.jpg)
Red = Original Case, Green = Alternative Case

# License
As the original design it was based on, this case is shared as CC-BY-SA 4.0.
All printing tests were performed on a Creality Ender3, all NURBS modeling is done with Rhino 5.
