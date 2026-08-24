---
title: "Multiple Memory, Socket and Color Faults After Reversing Ms. Pac-Man Modification"
description: "Firsthand Original Pac-Man PCB previously modified to play Ms. Pac-Man without daughter card repair: Multiple Memory, Socket and Color Faults After..."
layout: default
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-multiple-memory-color-faults/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pac-Man modified Ms Pac-Man; will not boot; 2A 2B 2C 2D; 2114; 283 sweep; wrong ghost color; white cherry; 4A; 7F; color RAM"
---
# Multiple Memory, Socket and Color Faults After Reversing Ms. Pac-Man Modification


## Repair Case Summary

This page documents a firsthand **Multiple Memory, Socket and Color Faults After Reversing Ms. Pac-Man Modification** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2019-03-15
- **Board:** Original Pac-Man PCB previously modified to play Ms. Pac-Man without daughter card
- **Category:** Boot / memory / color / socket
- **Symptoms:**
  - After reversing the old Ms. Pac-Man modification, the board would not boot.
  - After initial memory replacement, further problems remained.
  - On the diagnostics screen, the dark-blue ghost appeared orange/dark blue and the cherry appeared white.
- **Diagnostic observations / tests:**
  - ABC Diagnostics found three of four color RAMs at 2A-2D bad and all 2114 scratch memory bad.
  - After replacing those parts, the sweep holding the 283 was found loose and not making connection.
  - After replacing the sweep, diagnostics passed except for incorrect colors.
  - Further investigation found 4A and 7F incorrect or bad.
- **Components / locations investigated:** 2A-2D color RAM, 2114 scratch memory, 283 sweep/socket, 4A, 7F
- **Root cause:** Multiple faults: bad color RAMs, bad 2114 scratch memory, poor 283 connection, and incorrect/bad color devices at 4A and 7F.
- **Repair:** Replaced the color RAMs, all 2114 memory chips, the loose sweep for the 283, and the devices at 4A and 7F.
- **Result:** The documented faults were corrected through the listed replacements.
- **Search terms:** Pac-Man modified Ms Pac-Man; will not boot; 2A 2B 2C 2D; 2114; 283 sweep; wrong ghost color; white cherry; 4A; 7F; color RAM
- **Evidence:** Physically verified repair / firsthand repair log

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Sparkles or Stars Around Pac-Man and Ghosts](/arcade/pac-man-ms-pac-man/repairs/pac-man-sparkles-stars-5e-5f/)
- [Notches Missing From Pac-Man and Ghost Graphics](/arcade/pac-man-ms-pac-man/repairs/pac-man-notches-missing-sprites-5e-5f/)
- [Pinky Jitters During Vertical Movement](/arcade/pac-man-ms-pac-man/repairs/pac-man-pinky-jitter-3h/)
- [Garbled Pac-Man, Ghost and Fruit Sprites](/arcade/pac-man-ms-pac-man/repairs/pac-man-garbled-sprites-74ls174-1h/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
