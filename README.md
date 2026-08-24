# 555-Timer-PCB

A custom 2-layer printed circuit board layout for an NE555 timer circuit, designed using Cadence OrCAD / Allegro PCB Designer. This repository includes the source board files, custom padstacks, and CAM350-verified Gerber and Drill files ready for manufacturing.

## Project Overview
* **Core Component:** NE555 Timer IC
* **EDA Software:** Cadence OrCAD / Allegro PCB Designer (v22.1)
* **Layer Count:** 2-Layer (Top/Bottom Copper with VCC/GND routing)
* **Status:** Layout complete, DRC cleared, and Gerber files verified.

## Repository Contents
* **`/layout`**: Contains the source `.brd` file and custom `.pad` files (including custom vias like 24C12VIA).
* **`/manufacturing`**: The final CAM350-verified `.art` (Gerber) and `.drl` (Drill) files, ready for fabrication.
* **`/schematic`**: Source schematic design files.

## Design Highlights
* Configured custom via libraries and padpaths within the Cadence Physical Constraint Manager.
* Generated specialized manufacturing cut-paths utilizing the `Design_Outline` subclass.
* Verified layer alignment, soldermask openings, and silkscreen clearances using CAM350.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
**Brijesh Chauhan**
