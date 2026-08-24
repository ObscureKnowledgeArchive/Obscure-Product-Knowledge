---
title: "Dead Board, Watchdog Running, Broken Traces at 3S"
description: "Firsthand Original Pac-Man PCB repair: Dead Board, Watchdog Running, Broken Traces at 3S. Includes symptoms, diagnostic steps, root cause, PCB locations,..."
layout: default
breadcrumbs:
  - name: Arcade
  - name: Pac-Man & Ms. Pac-Man
  - name: PCB Repairs
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-dead-watchdog-broken-traces-3s/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pac-Man watchdog; dead board; no pulse 5M; no pulse 3P; no pulse 9C; 3S; 161; broken trace"
---
# Dead Board, Watchdog Running, Broken Traces at 3S


## Repair Case Summary

This page documents a firsthand **Dead Board, Watchdog Running, Broken Traces at 3S** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2017-06-07
- **Board:** Original Pac-Man PCB
- **Category:** Boot failure / watchdog / traces
- **Symptoms:**
  - Board completely dead.
  - Watchdog was going crazy.
  - No pulse at 5M, 3P, or 9C.
- **Diagnostic observations / tests:**
  - The 161 at 3S had been replaced previously.
  - Traces beneath the socket looked poor.
  - Removing the socket revealed bad traces at pins 2 and 5.
- **Components / locations investigated:** 3S, 161, 3S pin 2, 3S pin 5, 5M, 3P, 9C
- **Root cause:** Two broken/bad traces beneath the socket at 3S, pins 2 and 5.
- **Repair:** Repaired the pin 2 and pin 5 traces at 3S.
- **Result:** The board booted immediately.
- **Search terms:** Pac-Man watchdog; dead board; no pulse 5M; no pulse 3P; no pulse 9C; 3S; 161; broken trace
- **Evidence:** Physically verified repair / firsthand repair log

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Dead Board With BAD ROM 0 in Test Mode](/arcade/pac-man-ms-pac-man/repairs/pac-man-bad-rom-0-no-boot/)
- [Static Garbage Screen Caused by Z80 Socket](/arcade/pac-man-ms-pac-man/repairs/pac-man-static-garbage-z80-socket/)
- [Screen Full of Zeros With Irregular Black Blocks](/arcade/pac-man-ms-pac-man/repairs/pac-man-screen-zeros-bad-2114-4k/)
- [Screen Full of Red 2s Caused by Loose Sync Bus Controller](/arcade/pac-man-ms-pac-man/repairs/pac-man-red-2s-sync-bus-controller/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
