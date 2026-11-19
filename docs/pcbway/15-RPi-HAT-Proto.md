# Raspberry Pi HAT-size Proto Board

## Title
Raspberry Pi HAT-size Proto Board

## Short description (summary box)
HAT-size proto board: 40-pin header, a linked hole for every pin, BCM labels, dot grid.

## Tags
raspberry pi, hat, gpio, proto board

## Description (paste into the project description)

### Why I made this
In 2019 I shared a simple 100 x 50 mm DIY universal board. I kept using it, and I kept wishing it came in more sizes and in versions made for the boards I use every day. So I redrew it and built a whole family: 22 open-source prototype PCBs on one 2.54 mm grid, all with the same plated holes, labels and mounting holes. This board is one of them.

### What's on the board
- Official HAT size (65 x 56.5 mm) with 4 M2.5 holes 58 x 49 mm apart
- 40-pin header in the standard position, pin 1 square
- Every header pin has a linked hole, labelled with its BCM name
- Dot grid for your circuit
- 2.54 mm (0.1") grid: DIP chips, pin headers and breadboard parts fit directly
- 1.0 mm plated-through holes with 1.8 mm pads on both sides: pads don't lift when you rework
- Every board passes the design rule check with zero errors

### Specs
| Item | Value |
|---|---|
| Board size | 65 x 56.5 mm |
| Layers | 2 |
| Thickness | 1.6 mm FR-4 |
| Grid pitch | 2.54 mm |
| Hole / pad | 1.0 mm plated / 1.8 mm, both sides |
| Licence | CC BY-SA 4.0 |

### Good for
- Pi add-ons: sensors, relays, displays, buttons
- Home Assistant and automation builds

### Order settings
- 2 layers, FR-4, 1.6 mm
- HASL (lead-free is better if you give boards away)
- Any solder mask colour, white silkscreen
- No special options. Minimum hole is 1.0 mm

### Tips
- This is HAT-size, not a certified HAT: it has no ID EEPROM

### Part of the DIY Universal Boards family
22 open-source proto boards on one grid: dot-grid boards, stripboard, breadboard layouts, carriers for Pico / ESP32 / ESP8266 / Nano / D1 mini / C3 SuperMini / Blue Pill, Arduino Uno and Mega shields, a Raspberry Pi HAT-size board, an SMD adapter and PCB rulers.
All Gerbers and docs: https://github.com/ElectroIoT/DIY-Universal-Boards

Made by ElectroIoT.in - https://electroiot.in

## Files to upload
- Gerber: `gerber/Gerber_RPi-HAT-Proto.zip`
- Pictures: use photos of the real board, front and back, plus one with a finished build. If you have no photos yet, use a 3D render of the board, not an editor screenshot.
