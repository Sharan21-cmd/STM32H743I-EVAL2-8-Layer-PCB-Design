# STM32H743I-EVAL2 — 8-Layer PCB Design

## Overview

An eight-layer PCB design project based on the STM32H743I-EVAL2 reference design. The project explores schematic organization, component libraries, multilayer PCB layout, routing, and design-rule verification using Altium Designer.

## Project Highlights

- Eight-layer PCB layout workflow
- Multiple schematic sheets for MCU, power, memory, USB, Ethernet, audio, SD card, and peripheral interfaces
- Custom schematic and PCB library files
- Multilayer routing and design-rule debugging
- Reported final DRC result: **0 rule violations**

## Tools

- Altium Designer
- Altium schematic and PCB editors
- Design Rule Check (DRC)

## Repository Contents

- `STM32H743I-EVAL2.PrjPcb` — Altium PCB project
- `STM32H743I-EVAL2PCBDESIGN.PcbDoc` — PCB layout document
- `*.SchDoc` — Schematic sheets
- `*.PcbLib` — PCB footprint library
- `*.SchLib` — Schematic symbol library
- `CAPPERIPHERAL/`, `COMPONENTS/` — Component-related project resources

## Verification Status

The project has a reported DRC result of zero rule violations as of 16 October 2026.

This result describes the design-rule check only. It does not establish that the board has been manufactured, electrically tested, or validated in hardware.

## Reference Design and Licensing

This project is based on the STM32H743I-EVAL2 reference design. Original reference-design files and third-party libraries may be subject to their respective licenses and redistribution restrictions. Check the applicable terms before sharing these files publicly.

## Author

Sharan K U

## Project Status

PCB layout and design-rule debugging completed to the reported DRC status. Further electrical, manufacturing, and hardware validation may be required.
