---
title: "Garbled Static Graphics, No Boot, No Reset, Plus Loud Hum"
description: "Firsthand Original Pac-Man PCB repair: Garbled Static Graphics, No Boot, No Reset, Plus Loud Hum. Includes symptoms, diagnostic steps, root cause, PCB..."
layout: default
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-no-boot-rom-sockets-6e-6j/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pac-Man garbled static; no boot; no reset; ABC Diagnostics boots; ROM sockets; 6E; 6F; 6H; 6J; C50; speaker hum"
---
# Garbled Static Graphics, No Boot, No Reset, Plus Loud Hum


## Repair Case Summary

This page documents a firsthand **Garbled Static Graphics, No Boot, No Reset, Plus Loud Hum** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2018-06-06
- **Board:** Original Pac-Man PCB
- **Category:** Boot failure / ROM sockets / sound hum
- **Symptoms:**
  - Garbled static graphics on screen.
  - Board would not boot.
  - No reset.
  - ABC Diagnostics booted successfully.
  - A loud hum was present through the speakers.
- **Diagnostic observations / tests:**
  - Installing ABC Diagnostics requires removing ROMs 6E-6J; because diagnostics booted, one or more ROM sockets were suspected.
  - Diagnostics otherwise passed.
  - After all four 6E-6J sockets were replaced, the board booted and played normally.
  - Further inspection found capacitor C50 missing.
- **Components / locations investigated:** 6E, 6F, 6H, 6J, ROM sockets, C50
- **Root cause:** Bad ROM socket connection(s) in 6E-6J and missing capacitor C50.
- **Repair:** Replaced all four ROM sockets at 6E-6J and installed the missing C50.
- **Result:** The board booted and played perfectly; the speaker hum disappeared.
- **Search terms:** Pac-Man garbled static; no boot; no reset; ABC Diagnostics boots; ROM sockets; 6E; 6F; 6H; 6J; C50; speaker hum
- **Evidence:** Physically verified repair / firsthand repair log

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Dead Board With BAD ROM 0 in Test Mode](/arcade/pac-man-ms-pac-man/repairs/pac-man-bad-rom-0-no-boot/)
- [Static Garbage Screen Caused by Z80 Socket](/arcade/pac-man-ms-pac-man/repairs/pac-man-static-garbage-z80-socket/)
- [Screen Full of Zeros With Irregular Black Blocks](/arcade/pac-man-ms-pac-man/repairs/pac-man-screen-zeros-bad-2114-4k/)
- [Screen Full of Red 2s Caused by Loose Sync Bus Controller](/arcade/pac-man-ms-pac-man/repairs/pac-man-red-2s-sync-bus-controller/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
