# DIY Universal Boards: Project Pitch

## One line

**26 open-source PCBs, one family:** dot-grid boards, stripboard, breadboard-layout boards, carriers for the dev boards makers use every day, Arduino and Raspberry Pi proto shields, an SMD adapter and two PCB rulers. They're free to download, change and order.

## The short pitch (paste anywhere, ~80 words)

> In 2019 I shared a simple 100 × 50 mm DIY universal board. It was a plain board, but I kept reaching for it. I also kept wishing it came in other sizes, with power rails, as a breadboard copy, and in versions that fit my Pico, ESP32 and Nano. So I redrew it and built a complete family of 26 boards, with the same quality and specs everywhere. Every board is open source (CC BY-SA 4.0), with ready-to-order Gerbers.

## Why I made this

Every maker knows this moment. The circuit works on the breadboard, and now it has to become something real. The usual choices all have a catch:

- **Cheap perfboard** has single-sided pads that lift after one rework, holes that don't line up, and no labels.
- **Designing a custom PCB** for a one-off build takes days, and you wait two weeks to find a mistake.
- **Hand-wiring a dev board** onto perfboard means guessing which hole is GPIO 4.

I wanted boards that sit in the middle: as quick as perfboard, as solid as a real PCB, and printed with the information you actually need while soldering.

## What makes it different

| | Typical perfboard | DIY Universal Boards |
|---|---|---|
| Pads | Single-sided, lift easily | **Plated through, both sides**, survive rework |
| Holes | Often off-grid | **Exact 2.54 mm grid** on every proto board |
| Labels | None | Row/column numbers, **pin names** on every carrier |
| Dev boards | Guess the pins | Socket rows with **2 extra linked holes per pin** |
| Breadboard to PCB | Rewire everything | **Same layout as a breadboard**, move parts hole for hole |
| Mounting | Drill your own | **M3 holes** (or the real Arduino / Pi hole positions) |
| Source | Closed | **Open source**, Gerbers + docs on GitHub |

## The family

| Group | Boards |
|---|---|
| Dot-grid boards | 100×50 (V2), 100×100, 90×70, 60×40, 70×30 |
| Copper-linked layouts | Stripboard, Power Rail Proto, Breadboard PCB, Mini Breadboard |
| Dev-board carriers | Raspberry Pi Pico, ESP32 DevKit 38-pin, NodeMCU ESP8266, Arduino Nano, Wemos D1 mini, ESP32-C3 SuperMini, STM32 Blue Pill |
| Shields and HATs | Arduino Uno shield, Arduino Mega shield, Raspberry Pi HAT-size proto |
| Specials | SMD adapter (SOIC / SOT-23 / 0805 / 1206), PCB rulers 10 cm and 15 cm, LED chaser rulers 10 cm and 15 cm, Power Proto Board and Mini Power Module |

## How it scores on design, usability, creativity and content

**Design**
- A single design system: 1.0 mm plated holes, 1.8 mm pads, 2.54 mm grid and M3 corners on every board, so parts and habits carry over from one board to the next.
- Every board passes the design rule check with zero errors.
- Pin positions for shields and carriers come from published reference footprints and, where possible, top-view photos of the real boards (the 160 mil Arduino D7–D8 gap, the HAT header position, the Mega double row).

**Usability**
- Real labels on the copper side you solder on: rows, columns, GPIO names, + and − rails, pin 1 square pads.
- Carriers give every module pin 2 extra holes, so you never solder two wires into one hole.
- The NodeMCU and ESP32 carriers take both the narrow and the wide module versions.
- No special fab options are needed: 2 layers, 1.6 mm, HASL, minimum hole 1.0 mm.

**Creativity**
- It treats a "boring" perfboard as a product line, with one family covering prototype → breadboard copy → module carrier → shield.
- The PCB ruler doubles as a bench reference card: copper scales on **both** sides, drill and AWG wire gauges, trace widths with current ratings, and 21 labelled SMD footprints.

**Content**
- A full write-up for each board: specs, uses, order settings, soldering tips.
- Open source on GitHub with Gerbers, images and a README section per board.
- CC BY-SA 4.0: free to use, change and sell, with credit.

## 30-second video script

1. *(Breadboard with a working circuit)* "It works on the breadboard. Now what?"
2. *(Cheap perfboard, pad lifting)* "Cheap perfboard falls apart. A custom PCB takes two weeks."
3. *(Fan out the boards)* "So I made DIY Universal Boards: 26 open-source PCBs."
4. *(Breadboard PCB beside the breadboard)* "Copy your breadboard hole for hole…"
5. *(Pico / ESP32 carrier)* "…drop in your Pico, ESP32 or Nano, with every pin labelled…"
6. *(Ruler on the bench)* "…and measure it all with the PCB ruler."
7. *(GitHub page)* "Free Gerbers. Order the boards you need. Link below. ElectroIoT.in"

## Links

- GitHub (Gerbers, images, docs): https://github.com/ElectroIoT/DIY-Universal-Boards
- Website: https://electroiot.in
- License: CC BY-SA 4.0
