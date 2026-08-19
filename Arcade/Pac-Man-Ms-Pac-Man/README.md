---
title: "Pac-Man & Ms. Pac-Man PCB Repair Archive — Troubleshooting Guide"
description: "Firsthand Pac-Man and Ms. Pac-Man arcade PCB repair logs organized by symptom, including boot failures, garbage screens, sprite problems, sound faults, RAM/ROM failures, coin input problems, power issues, sockets, traces, and component locations."
layout: default
permalink: "/arcade/pac-man-ms-pac-man/"
category: "Arcade PCB Repair"
---

# Pac-Man & Ms. Pac-Man PCB Repair Archive

This archive contains firsthand repair records for original Midway Pac-Man and Ms. Pac-Man arcade PCBs. The repairs are organized primarily by **symptom**, so a technician can begin with what the board is actually doing and follow the relevant repair case.

These are documented repair cases, not a claim that every identical symptom has the same cause. Each linked repair page preserves the observed symptoms, diagnostic process, components or PCB locations investigated, root cause found in that case, repair performed, and result.

## Pac-Man PCB Troubleshooting by Symptom

### Won't Boot, Dead Board, Garbage Screen, or Reset Problems

- **BAD ROM 0, blank screen, no sound** — program ROM problem in the 6E ROM area.  
  [Pac-Man dead board with BAD ROM 0](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-bad-rom-0-no-boot/)

- **Static garbage screen; pressing the Z80 changes the display** — faulty Z80 socket.  
  [Pac-Man static garbage screen caused by Z80 socket](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-static-garbage-z80-socket/)

- **Screen full of zeros with irregular black blocks** — bad 2114 scratchpad RAM, isolated to 4K in the documented repair.  
  [Pac-Man screen full of zeros — bad 2114 RAM at 4K](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-screen-zeros-bad-2114-4k/)

- **Screen full of red 2s** — poor connection at the Z80 Sync Bus Controller card.  
  [Pac-Man screen full of red 2s — Sync Bus Controller](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-red-2s-sync-bus-controller/)

- **Completely dead board with watchdog activity and missing pulses** — broken traces beneath the previously replaced device/socket at 3S.  
  [Pac-Man dead board and watchdog — broken traces at 3S](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-dead-watchdog-broken-traces-3s/)

- **Garbled static graphics, no boot, and no reset; ABC Diagnostics will boot** — bad ROM socket connection(s) in the 6E–6J area.  
  [Pac-Man no boot — ROM sockets 6E through 6J](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-no-boot-rom-sockets-6e-6j/)

- **Static garbage in blocks, dead Z80 address/data activity, failed reset** — bad 74LS02 at 7L in the documented repair.  
  [Pac-Man reset failure — 74LS02 at 7L](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-reset-failure-74ls02-7l/)

### Graphics, Maze, Character, and Sprite Problems

- **Sparkles or stars around Pac-Man and ghosts** — bad 5E/5F devices in the documented case.  
  [Pac-Man sparkles and stars — 5E/5F](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-sparkles-stars-5e-5f/)

- **Notch missing from Pac-Man and notches missing from ghost heads** — bad original masked ROMs at 5E/5F.  
  [Pac-Man and ghost graphics with missing notches — 5E/5F](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-notches-missing-sprites-5e-5f/)

- **Pinky jitters or twitches while moving vertically** — fault associated with 3H; replacement of the device at 3H corrected the documented board.  
  [Pac-Man Pinky jitter during vertical movement — 3H](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-pinky-jitter-3h/)

- **Pac-Man, ghosts, and fruit are garbled or divided into blocks/quadrants** — bad 74LS174 at 1H.  
  [Pac-Man garbled sprites — 74LS174 at 1H](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-garbled-sprites-74ls174-1h/)

- **Pac-Man and all ghosts are stuck in the upper-left corner** — bad 7489 at 2F.  
  [Pac-Man characters stuck in upper-left corner — 7489 at 2F](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-characters-upper-left-7489-2f/)

- **Rapidly flashing ghosts and flashing garbage** — bad scratchpad memory IC at 4R.  
  [Pac-Man flashing ghosts and garbage — 4R](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-flashing-ghosts-garbage-4r/)

- **Two Pac-Man characters briefly appear, ghosts jump around, characters look translucent** — damaged 285 socket.  
  [Pac-Man intermittent translucent characters — bad 285 socket](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-translucent-characters-285-socket/)

- **Wrong character/fruit colors after other memory repairs** — documented case involved color RAM, 2114 memory, a poor 283 connection, and devices at 4A and 7F.  
  [Pac-Man multiple memory and color faults](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-multiple-memory-color-faults/)

- **Partial maze with large horizontal dead spaces** — bad D2115 at 2A in the documented repair.  
  [Pac-Man partial maze — D2115 at 2A](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-partial-maze-d2115-2a/)

### Sound Problems

- **No sound at all, but the game otherwise plays correctly** — signal tracing led through 11A, 8K, 2M and 2L to a bad 74LS139 at 7M.  
  [Pac-Man no sound — 74LS139 at 7M](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-no-sound-74ls139-7m/)

- **Intermission music out of tempo and a test-mode sound missing** — broken trace between 1M pin 3 and R2, with prior work at the CD4066 at 1M.  
  [Pac-Man incorrect intermission sound — 1M broken trace](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-intermission-sound-1m-broken-trace/)

- **Slightly distorted siren, intermission music, and test sounds** — swapping the device at 1M corrected the documented board.  
  [Pac-Man distorted sound — 1M](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-distorted-sound-1m/)

- **Ms. Pac-Man sounds are crunchy and fuzzy** — C47 measured out of range.  
  [Ms. Pac-Man crunchy or fuzzy sound — C47](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/ms-pac-man-crunchy-fuzzy-sound-c47/)

- **Missing background sounds with an aftermarket Ms. Pac-Man daughter card** — documented case involved custom-burned ROMs and missing C49.  
  [Ms. Pac-Man missing background sound — custom ROMs and C49](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/ms-pac-man-missing-background-sound-custom-roms/)

- **Loud speaker hum accompanying no-boot/ROM-socket trouble** — the documented board also had missing C50.  
  [Pac-Man no boot, bad ROM sockets, and speaker hum](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-no-boot-rom-sockets-6e-6j/)

### Coin and Credit Problems

- **Game will not coin up through the credit switch** — replacing 8H did not solve the fault; replacing the 74LS367 at 8E did.  
  [Pac-Man will not coin up — 74LS367 at 8E](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-will-not-coin-up-74ls367-8e/)

### Power-Related Problems

- **Ms. Pac-Man and ghosts move or appear out of position in the cabinet despite working on a test rig** — the documented switching supply measured nearly 5.40 V; reducing it to 5.00 V restored normal operation.  
  [Ms. Pac-Man characters out of position — high +5 V supply](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/ms-pac-man-characters-out-of-position-high-5v/)

### Memory and ROM Problems

Relevant documented cases include:

- [BAD ROM 0 / program ROM failure](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-bad-rom-0-no-boot/)
- [Screen full of zeros / bad 2114 RAM at 4K](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-screen-zeros-bad-2114-4k/)
- [Flashing ghosts / scratchpad memory at 4R](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-flashing-ghosts-garbage-4r/)
- [No boot / ROM sockets at 6E–6J](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-no-boot-rom-sockets-6e-6j/)
- [Multiple memory and color faults](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-multiple-memory-color-faults/)
- [Partial maze / D2115 at 2A](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-partial-maze-d2115-2a/)

### Sockets, Connections, Traces, and Previous PCB Repairs

Several failures in these logs were caused not by the IC itself, but by sockets, connections, traces, or earlier repair work:

- [Z80 socket causing static garbage and no boot](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-static-garbage-z80-socket/)
- [Loose Z80 Sync Bus Controller causing red 2s](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-red-2s-sync-bus-controller/)
- [Broken trace at 1M affecting sound](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-intermission-sound-1m-broken-trace/)
- [Broken traces beneath 3S causing a dead/watchdog board](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-dead-watchdog-broken-traces-3s/)
- [Bad ROM sockets at 6E–6J](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-no-boot-rom-sockets-6e-6j/)
- [Damaged 285 socket causing intermittent graphics](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-translucent-characters-285-socket/)

## General Pac-Man / Ms. Pac-Man PCB Reference Notes

### Midway Device Numbers Recorded in the Original Notes

| PCB location | Midway number |
| --- | --- |
| 1M | M932B-46H0 |
| 3M | M932A-46H0 |
| 4A | M932C-46HO |
| 7F | M932O-07AXN-A |

These identifiers are reproduced as recorded in the original repair notes.

### Sound Troubleshooting Notes

The original notes record the following troubleshooting sequence when the speaker and harness are already known to be good:

1. Turn the sound up high and gently run a finger over the solder-side pins of 11A. Crackling should be heard through the speaker; if not, 11A may be bad.
2. Check resistors and capacitors in the sound circuit, particularly when sound is present but distorted.
3. Check 8K pin 5 for a high signal.
4. Check outputs at 7M pins 11 and 12. The notes identify pin 11 as HP and pin 12 as HLP.

See also: [Pac-Man no sound — signal tracing to 74LS139 at 7M](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-no-sound-74ls139-7m/).

### ABC Diagnostics Tool Observation

The original repair notes record an important diagnostic observation:

If a Pac-Man PCB functions correctly while the ABC Diagnostics Tool is installed but fails after the board is returned to factory configuration, investigate the **6E, 6F, 6H and 6J ROMs, ROM sweeps/sockets, or traces in that circuit**.

A documented example is the board that would not boot normally but successfully booted the diagnostics software:

[Pac-Man no boot — ROM sockets 6E through 6J](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-no-boot-rom-sockets-6e-6j/)

## Repair Practice Note: Burn-In After Repair

One repair produced an additional practical lesson: a freshly repaired Pac-Man PCB should be allowed to run for at least an hour or two. A board that initially appears fully repaired may reveal another problem after reaching operating temperature.

This observation came from the documented coin/credit repair:

[Pac-Man will not coin up — 74LS367 at 8E](/Obscure-Product-Knowledge/arcade/pac-man-ms-pac-man/repairs/pac-man-will-not-coin-up-74ls367-8e/)

## About These Repair Records

These records originated from hands-on Pac-Man and Ms. Pac-Man PCB troubleshooting and repair work. They are presented as **documented repair cases**, not universal diagnostic rules. Similar symptoms can have different electrical causes.

When troubleshooting, use the symptom descriptions to identify relevant cases, then follow the diagnostic observations rather than replacing a component solely because it fixed another board.
