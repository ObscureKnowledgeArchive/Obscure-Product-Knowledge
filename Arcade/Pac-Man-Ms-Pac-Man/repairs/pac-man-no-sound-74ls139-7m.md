---
title: "No Sound: Signal Trace Leads to 74LS139 at 7M"
description: "Firsthand Original Pac-Man PCB repair: No Sound: Signal Trace Leads to 74LS139 at 7M. Includes symptoms, diagnostic steps, root cause, PCB locations,..."
layout: default
breadcrumbs:
  - name: Arcade
  - name: Pac-Man & Ms. Pac-Man
  url: /arcade/pac-man-ms-pac-man/
  - name: PCB Repairs
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-no-sound-74ls139-7m/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pac-Man no sound; 7M; 74LS139; 11A crackle test; 8K pin 5; 2M; 2L; logic probe; sound tracing"
---
# No Sound: Signal Trace Leads to 74LS139 at 7M


## Repair Case Summary

This page documents a firsthand **No Sound: Signal Trace Leads to 74LS139 at 7M** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2019-08-09
- **Board:** Original Pac-Man PCB
- **Category:** Sound / logic tracing
- **Symptoms:**
  - Board booted and played perfectly but had no sound at all.
- **Diagnostic observations / tests:**
  - Speaker/connections were ruled out first.
  - With volume high, rubbing the solder-side pins of amp IC 11A produced speaker crackle, indicating the downstream amplifier path responded.
  - Sound-circuit resistors checked normally.
  - 8K pin 5 was high as expected.
  - At 2M, pins 3, 4, 7, 8 and outputs 6, 9, 12, 16, 19 showed bad signals.
  - 2M inputs 3, 4, 7, 8 receive signals from 2L.
  - 2L pin 3 was missing a pulse; that input comes from 7M pin 11.
  - At 7M (74LS139), output pins 5, 11 and 12 had irregular signals while the remaining pins checked normally.
  - Piggybacking a new 74LS139 at 7M restored all sounds.
- **Components / locations investigated:** 11A, 8K pin 5, 2M, 2L pin 3, 7M, 74LS139, 7M pins 5, 11, 12
- **Root cause:** Bad 74LS139 at 7M.
- **Repair:** Replaced the 74LS139 at 7M.
- **Result:** All sounds returned and played correctly.
- **Search terms:** Pac-Man no sound; 7M; 74LS139; 11A crackle test; 8K pin 5; 2M; 2L; logic probe; sound tracing
- **Evidence:** Physically verified repair / firsthand repair log

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Missing and Out-of-Tempo Sounds From Broken Trace at 1M](/arcade/pac-man-ms-pac-man/repairs/pac-man-intermission-sound-1m-broken-trace/)
- [Slightly Distorted Sound Effects and Intermission Music](/arcade/pac-man-ms-pac-man/repairs/pac-man-distorted-sound-1m/)
- [Crunchy and Fuzzy Sound Effects](/arcade/pac-man-ms-pac-man/repairs/ms-pac-man-crunchy-fuzzy-sound-c47/)
- [Missing Background Siren and Hum With Aftermarket Ms. Pac-Man Daughter Card](/arcade/pac-man-ms-pac-man/repairs/ms-pac-man-missing-background-sound-custom-roms/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
