# RP2040 Base PCB design

This KiCad project contains a base RP2040 schematic and PCB layout. To use these files:

1. Create a new KiCad 6 Project
2. Open this project in another KiCad 6 window
3. Copy the schematic contents to the clipboard
4. Do _Edit_ > _Paste Special_ in your new schematic and select _Keep existing reference designators, even if they are duplicated_
5. Copy the PCB design to the clipboard
6. Paste the PCB design into your new project's PCB design

It's important to do the paste special in step 4 to ensure the reference designators match between the schematic and the PCB.

JLCPCB component numbers and footprints are included in the schematic as custom symbol properties.
