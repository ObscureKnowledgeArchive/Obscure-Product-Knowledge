---
title: "Static Garbage, Dead Address/Data Lines and Failed Reset"
description: "Firsthand Original Pac-Man PCB repair: Static Garbage, Dead Address/Data Lines and Failed Reset. Includes symptoms, diagnostic steps, root cause, PCB..."
layout: default
breadcrumbs:
  - name: Arcade
  - name: Pac-Man & Ms. Pac-Man
  - name: PCB Repairs
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-reset-failure-74ls02-7l/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pac-Man reset failure; static garbage blocks; dead address lines; dead data lines; Z80 pin 26; 7L; 74LS02; 9C; no boot"
---
# Static Garbage, Dead Address/Data Lines and Failed Reset


## Repair Case Summary

This page documents a firsthand **Static Garbage, Dead Address/Data Lines and Failed Reset** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2019-08-19
- **Board:** Original Pac-Man PCB
- **Category:** Reset circuit / boot failure
- **Symptoms:**
  - Static garbage displayed in blocks with large horizontal spaces between them.
  - Z80 data and address lines were dead with no signal.
  - Reset function was not working.
  - Temporarily applying a high signal to Z80 pin 26 allowed the game to boot and run, although display problems remained.
- **Diagnostic observations / tests:**
  - Reset circuit was traced.
  - 9C and 7L showed abnormal signals.
  - 9C was replaced first, but the problem remained.
  - After other reset-circuit components were ruled out, 7L was replaced and the board booted.
- **Components / locations investigated:** Z80 pin 26, 9C, 7L, 74LS02
- **Root cause:** Bad 74LS02 at 7L in the reset circuit.
- **Repair:** Replaced the 74LS02 at 7L.
- **Result:** The board booted and played; a separate graphical fault remained and was repaired in the following entry.
- **Repair note:** Linked repair: the same PCB had a remaining graphics fault documented in the next 2019-08-19 record.
- **Search terms:** Pac-Man reset failure; static garbage blocks; dead address lines; dead data lines; Z80 pin 26; 7L; 74LS02; 9C; no boot
- **Evidence:** Physically verified repair / firsthand repair log

## Related Repair on the Same PCB

After this reset-circuit repair, the same board still had a separate graphics problem. See [Pac-Man partial maze with horizontal dead spaces — D2115 at 2A](/arcade/pac-man-ms-pac-man/repairs/pac-man-partial-maze-d2115-2a/).

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Partial Maze With Large Horizontal Dead Spaces](/arcade/pac-man-ms-pac-man/repairs/pac-man-partial-maze-d2115-2a/)
- [Dead Board With BAD ROM 0 in Test Mode](/arcade/pac-man-ms-pac-man/repairs/pac-man-bad-rom-0-no-boot/)
- [Static Garbage Screen Caused by Z80 Socket](/arcade/pac-man-ms-pac-man/repairs/pac-man-static-garbage-z80-socket/)
- [Screen Full of Zeros With Irregular Black Blocks](/arcade/pac-man-ms-pac-man/repairs/pac-man-screen-zeros-bad-2114-4k/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
