---
title: "Missing and Out-of-Tempo Sounds From Broken Trace at 1M"
description: "Firsthand Original Pac-Man PCB repair: Missing and Out-of-Tempo Sounds From Broken Trace at 1M. Includes symptoms, diagnostic steps, root cause, PCB..."
layout: default
breadcrumbs:
  - name: Arcade
  - name: Pac-Man & Ms. Pac-Man
  url: /arcade/pac-man-ms-pac-man/
  - name: PCB Repairs
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-intermission-sound-1m-broken-trace/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pac-Man sound wrong; intermission music out of tempo; missing test sound; 1M; CD4066; R2; broken trace; sound circuit"
---
# Missing and Out-of-Tempo Sounds From Broken Trace at 1M


## Repair Case Summary

This page documents a firsthand **Missing and Out-of-Tempo Sounds From Broken Trace at 1M** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2017-04-08
- **Board:** Original Pac-Man PCB
- **Category:** Sound
- **Symptoms:**
  - Sound was incorrect, especially during intermission scenes.
  - In test mode there was no sound when the joystick was pressed down.
  - Parts of the intermission music played out of tempo.
- **Diagnostic observations / tests:**
  - Logic-probe troubleshooting narrowed the issue to the CD4066 at 1M.
  - The 4066 had been replaced previously without a socket and appeared to be a used part.
  - Continuity testing found a broken trace between 1M pin 3 and resistor R2.
- **Components / locations investigated:** 1M, CD4066, 1M pin 3, R2
- **Root cause:** Broken trace from 1M pin 3 to R2; questionable prior 4066 installation.
- **Repair:** Repaired the trace under 1M, installed a socket, and installed a good 4066.
- **Result:** All sounds were restored.
- **Search terms:** Pac-Man sound wrong; intermission music out of tempo; missing test sound; 1M; CD4066; R2; broken trace; sound circuit
- **Evidence:** Physically verified repair / firsthand repair log

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Slightly Distorted Sound Effects and Intermission Music](/arcade/pac-man-ms-pac-man/repairs/pac-man-distorted-sound-1m/)
- [Crunchy and Fuzzy Sound Effects](/arcade/pac-man-ms-pac-man/repairs/ms-pac-man-crunchy-fuzzy-sound-c47/)
- [Missing Background Siren and Hum With Aftermarket Ms. Pac-Man Daughter Card](/arcade/pac-man-ms-pac-man/repairs/ms-pac-man-missing-background-sound-custom-roms/)
- [No Sound: Signal Trace Leads to 74LS139 at 7M](/arcade/pac-man-ms-pac-man/repairs/pac-man-no-sound-74ls139-7m/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
