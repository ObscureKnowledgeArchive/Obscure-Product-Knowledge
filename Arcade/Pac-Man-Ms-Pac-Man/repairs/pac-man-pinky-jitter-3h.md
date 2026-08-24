---
title: "Pinky Jitters During Vertical Movement"
description: "Firsthand Original Pac-Man PCB repair: Pinky Jitters During Vertical Movement. Includes symptoms, diagnostic steps, root cause, PCB locations, repair and..."
layout: default
permalink: "/arcade/pac-man-ms-pac-man/repairs/pac-man-pinky-jitter-3h/"
category: "Pac-Man / Ms. Pac-Man PCB Repair"
keywords: "Pinky jitter; Pinky twitch; ghost movement glitch; vertical ghost movement; 3F; 3H; 8216; ABC Diagnostics; sprite movement"
---
# Pinky Jitters During Vertical Movement


## Repair Case Summary

This page documents a firsthand **Pinky Jitters During Vertical Movement** repair case.
It is intended for technicians and collectors troubleshooting original Pac-Man or Ms. Pac-Man arcade PCB hardware.

- **Date:** 2017-04-16
- **Board:** Original Pac-Man PCB
- **Category:** Sprite movement / graphics
- **Symptoms:**
  - Board booted and played normally except for one jittery ghost.
  - Pinky twitched while moving up and down.
  - Other ghosts behaved normally.
  - ABC Diagnostics sprite-movement test reproduced the erratic movement.
- **Diagnostic observations / tests:**
  - ABC Diagnostics identified 3F and 3H as associated with sprite movement.
  - Piggybacking 3F with a new 7489 produced no change.
  - Piggybacking 3H stopped the glitches.
- **Components / locations investigated:** 3F, 3H, 8216 at 3H
- **Root cause:** Fault associated with the device at 3H.
- **Repair:** Removed the old 8216 at 3H, installed a socket, and installed a replacement chip.
- **Result:** Pinky's movement returned to normal.
- **Search terms:** Pinky jitter; Pinky twitch; ghost movement glitch; vertical ghost movement; 3F; 3H; 8216; ABC Diagnostics; sprite movement
- **Evidence:** Physically verified repair / firsthand repair log

## Related Pac-Man / Ms. Pac-Man Repair Cases

- [Sparkles or Stars Around Pac-Man and Ghosts](/arcade/pac-man-ms-pac-man/repairs/pac-man-sparkles-stars-5e-5f/)
- [Notches Missing From Pac-Man and Ghost Graphics](/arcade/pac-man-ms-pac-man/repairs/pac-man-notches-missing-sprites-5e-5f/)
- [Garbled Pac-Man, Ghost and Fruit Sprites](/arcade/pac-man-ms-pac-man/repairs/pac-man-garbled-sprites-74ls174-1h/)
- [Pac-Man and Ghosts Stuck in Upper-Left Corner](/arcade/pac-man-ms-pac-man/repairs/pac-man-characters-upper-left-7489-2f/)

## How to Use This Repair Record

This is a firsthand physical repair case. The same symptom on another Pac-Man or Ms. Pac-Man PCB can have a different electrical cause. Use the documented diagnostic observations and tests to guide troubleshooting rather than replacing a component solely because it repaired this board.

[← Back to the Pac-Man / Ms. Pac-Man PCB Repair Archive](/arcade/pac-man-ms-pac-man/)
