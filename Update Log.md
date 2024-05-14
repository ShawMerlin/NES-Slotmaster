## Known Issues <BR>
Certain Everdrive N8's are not booting or booting with graphical issues. (5/14/2024) <br>
- This is impacted with the V1.8 board versions. <br>
- The issue is not due to the 8 expansion pins on the header cable. That was incorrect information applied to the silkscreen. <br>
- This is currently being researched to find the differences and what the root cause of this. <br>
- Potentially a Power draw issue with the size of the traces, also might be related to the ribbon cable being too long. <br> <br>

Some cartridges are not compatible <br>
- https://github.com/ShawMerlin/NES-Slotmaster/blob/main/GamesNotCompatible.md <br>

Slotmaster V1.7 doesn't connect Pin56 <br>
- https://github.com/ShawMerlin/NES-Slotmaster/blob/main/Slotmaster%20DIY%20Version/Better_Compatibility_Fix.md <br> <br>

## Flex Version 1.8b <BR>
Will release soon <br>
- Uses SMD FPC Flex connectors so that flat cables can be used.  Far less soldering. <br>
- Has a footprint for a ATTiny13 so the Krikzz AVRCIC can be used (if desired). <br> <br>

## DIY Version 1.8d <BR>
Gerber Files are available the under Slotmaster DIY Version folder <br>
- Includes the 8 pin breakout of all expansion ports so all 72 pins can be connected <br>
- Has a footprint for a ATTiny13 so the Krikzz AVRCIC can be used (if desired). <br> <br>

## Version 1.8 <BR>
Released 04/22/2024 <BR>
- Connected Pins 15 (IRQ) and 56 (PPU-WR) to ensure 100% Game Compatibility <br>
- Added an 8 Pin Header (2x4) to the top and bottom board to connect the EXP ports (if needed) <br>
- Increased the trace size on the VCC & GND from .25mm to .5mm <br>
- Added a logo for Laser Bear who helped redesign the Cartridge Slot and who is also offering these kits for sale <br>
<BR> <BR>

## Version 1.7 <BR>
Released 03/31/2024 <BR>
- First Public Release <br>
