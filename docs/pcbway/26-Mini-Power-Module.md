# Mini Power Module (DC jack / USB-C to 5 V + 3.3 V)

## Title
Mini Power Module (DC jack / USB-C to 5 V + 3.3 V)

## Short description (summary box)
Small power module: DC jack or USB-C in, 5 V and 3.3 V out on a 2.54 mm header for breadboards and proto boards.

## Tags
power module, breadboard power, 7805, ams1117, usb-c, dc jack

## Description (paste into the project description)

### Why I made this
In 2019 I shared a simple 100 x 50 mm DIY universal board. I kept using it, and I kept wishing it came in more sizes and in versions made for the boards I use every day. So I redrew it and built a whole family of 26 open-source boards: proto boards on one 2.54 mm grid, dev-board carriers, shields and PCB rulers, all with the same quality and clear labels. This board is one of them.

### What's on the board
- DC jack 5.5 x 2.1 mm (7-12 V) with reverse-polarity diode, or USB-C 5 V (CC resistors + 1 A PTC fuse)
- 5 V from an L7805 (TO-220, takes a clip-on heatsink) and 3.3 V from an AMS1117 (about 0.8 A)
- 3 A slide switch for the outputs, green power LEDs on 5 V and 3.3 V
- Ready for assembly: BOM with manufacturer part numbers and pick-and-place file included
- 1x8 2.54 mm output header: VIN, GND, 5V, 5V, GND, 3V3, 3V3, GND (plugs into a breadboard)
- 2 plated M3 mounting holes

### Specs
| Item | Value |
|---|---|
| Board size | 55 x 35 mm |
| Layers | 2 |
| Thickness | 1.6 mm FR-4 |
| Licence | CC BY-SA 4.0 |

### Good for
- Powering breadboard projects
- Adding 5 V and 3.3 V to any proto board

### Order settings
- 2 layers, FR-4, 1.6 mm
- HASL (lead-free is better if you give boards away)
- Any solder mask colour, white silkscreen
- No special options. Minimum hole is 1.0 mm

### Tips
- 7805 heat: keep 12 V loads under about 0.5 A, or use a 9 V adapter
- Check C1 and diode polarity before soldering
- Design passed the design rule check (0 errors) but has not been built yet

### Part of the DIY Universal Boards family
26 open-source boards: dot-grid boards, stripboard, breadboard layouts, carriers for Pico / ESP32 / ESP8266 / Nano / D1 mini / C3 SuperMini / Blue Pill, Arduino Uno and Mega shields, a Raspberry Pi HAT-size board, an SMD adapter, PCB rulers, LED chaser rulers and power-supply boards.
All Gerbers and docs: https://github.com/ElectroIoT/DIY-Universal-Boards

Made by ElectroIoT.in - https://electroiot.in

## Files to upload
- Gerber: `gerber/Gerber_Mini-Power-Module.zip`
- BOM (for assembly): `assembly/BOM_Mini-Power-Module_PCBWay.csv`
- Pick and place: `assembly/PickAndPlace_Mini-Power-Module.csv`
- Schematic picture: `docs/power-supply-schematic.png`
- Pictures: use photos of the real board, front and back, plus one with a finished build. If you have no photos yet, use a 3D render of the board, not an editor screenshot.
