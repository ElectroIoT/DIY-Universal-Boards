# LED Chaser PCB Ruler 10 cm

## Title
LED Chaser PCB Ruler 10 cm

## Short description (summary box)
10 cm PCB ruler with a rainbow LED chaser: 555 + 4017, one LED at every cm (1-10 cm), CR2032 powered, all parts on top, flat back.

## Tags
pcb ruler, led chaser, 555 timer, 4017, smd kit, soldering practice

## Description (paste into the project description)

### Why I made this
In 2019 I shared a simple 100 x 50 mm DIY universal board. I kept using it, and I kept wishing it came in more sizes and in versions made for the boards I use every day. So I redrew it and built a whole family of 24 open-source boards: proto boards on one 2.54 mm grid, dev-board carriers, shields and PCB rulers, all with the same quality and clear labels. This board is one of them.

### What's on the board
- A rainbow light runs along the scale: one LED at every cm (1-10 cm)
- TLC555 CMOS timer + 74HC4017 decade counter, runs from a CR2032 coin cell
- Speed trimmer (about 1.4 to 12 steps per second) and ON/OFF slide switch
- ALL parts on the top side: the back is flat, so the ruler still lies flat for measuring
- mm and inch copper scales on both sides, drill gauge 0.5-2.0 mm
- Gold exposed-copper "ElectroIoT.in" logo, formulas and colour code on the back
- Every part is SMD (SOIC-8, SOIC-16, 0805): a great SMD soldering practice kit
- Ready for assembly: BOM with manufacturer part numbers and pick-and-place file included

### Specs
| Item | Value |
|---|---|
| Board size | 120 x 34 mm |
| Layers | 2 |
| Thickness | 1.6 mm FR-4 |
| Licence | CC BY-SA 4.0 |

### Good for
- Gift and showpiece for makers and students
- SMD soldering workshops and kits
- Learning 555 timers and counters

### Order settings
- 2 layers, FR-4, 1.6 mm
- Surface finish: ENIG (gold) for the best look, HASL also works
- Black or blue solder mask makes the gold stand out, white silkscreen

### Tips
- Order matte black mask + white silkscreen + ENIG for gold scales on black
- LED colours: red, orange, yellow, yellow-green (all light from 3 V). Blue / white need 5 V
- Put the LED cathodes toward the top edge, fit the CR2032 + side up, and keep solder off the round gold battery pad
- Designs passed the design rule check (0 errors) but have not been built yet

### Part of the DIY Universal Boards family
24 open-source boards: dot-grid boards, stripboard, breadboard layouts, carriers for Pico / ESP32 / ESP8266 / Nano / D1 mini / C3 SuperMini / Blue Pill, Arduino Uno and Mega shields, a Raspberry Pi HAT-size board, an SMD adapter, PCB rulers and LED chaser rulers.
All Gerbers and docs: https://github.com/ElectroIoT/DIY-Universal-Boards

Made by ElectroIoT.in - https://electroiot.in

## Files to upload
- Gerber: `gerber/Gerber_LED-Chaser-Ruler-10cm.zip`
- BOM (for assembly): `assembly/BOM_LED-Chaser-Ruler-10cm_PCBWay.csv`
- Pick and place: `assembly/PickAndPlace_LED-Chaser-Ruler-10cm.csv`
- Schematic picture: `docs/led-chaser-ruler-schematic.png`
- Pictures: use photos of the real board, front and back, plus one with a finished build. If you have no photos yet, use a 3D render of the board, not an editor screenshot.
