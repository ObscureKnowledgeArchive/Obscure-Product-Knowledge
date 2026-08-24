---
title: "Partial Maze With Large Horizontal Dead Spaces"
description: "Firsthand Original Pac-Man PCB; same board as preceding reset-circuit repair repair: Partial Maze With Large Horizontal Dead Spaces. Includes symptoms,..."
layout: default
breadcrumbs:
  - name: Arcade
  - name: Pac-Man & Ms. Pac-Man
  url: /arcade/pac-man-ms-pac-man/
  - name: PCB Repairs
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-partial-maze-d2115-2a/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pac-Man partial maze; horizontal dead spaces; maze missing; 2A; D2115; 3A; 3B; 3D; video RAM; graphics"
---
# Partial Maze With Large Horizontal Dead Spaces


## Repair Case Summary

This page documents a firsthand **Partial Maze With Large Horizontal Dead Spaces** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2019-08-19
- **Board:** Original Pac-Man PCB; same board as preceding reset-circuit repair
- **Category:** Graphics / video RAM
- **Symptoms:**
  - Maze displayed only partially.
  - Large horizontal dead spaces appeared in the maze.
  - Removing previously socketed 3D while the board was running made the maze display perfectly, but all characters disappeared.
- **Diagnostic observations / tests:**
  - 3A and 3B were receiving bad signals.
  - Tracing narrowed the issue to the 2A-2D series.
  - Piggybacking 2A with a known-good D2115 returned the screen to normal.
- **Components / locations investigated:** 3D, 3A, 3B, 2A-2D, 2A, D2115
- **Root cause:** Bad D2115 at 2A.
- **Repair:** Replaced the D2115 at 2A.
- **Result:** The screen returned to normal.
- **Repair note:** This is the second repair on the PCB whose reset failure was corrected by replacing 7L.
- **Search terms:** Pac-Man partial maze; horizontal dead spaces; maze missing; 2A; D2115; 3A; 3B; 3D; video RAM; graphics
- **Evidence:** Physically verified repair / firsthand repair log

## Related Repair on the Same PCB

This was the same PCB whose reset failure was first corrected by replacing the 74LS02 at 7L. See [Pac-Man reset failure — 74LS02 at 7L](/arcade/pac-man-ms-pac-man/repairs/pac-man-reset-failure-74ls02-7l/).

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Static Garbage, Dead Address/Data Lines and Failed Reset](/arcade/pac-man-ms-pac-man/repairs/pac-man-reset-failure-74ls02-7l/)
- [Sparkles or Stars Around Pac-Man and Ghosts](/arcade/pac-man-ms-pac-man/repairs/pac-man-sparkles-stars-5e-5f/)
- [Notches Missing From Pac-Man and Ghost Graphics](/arcade/pac-man-ms-pac-man/repairs/pac-man-notches-missing-sprites-5e-5f/)
- [Pinky Jitters During Vertical Movement](/arcade/pac-man-ms-pac-man/repairs/pac-man-pinky-jitter-3h/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
