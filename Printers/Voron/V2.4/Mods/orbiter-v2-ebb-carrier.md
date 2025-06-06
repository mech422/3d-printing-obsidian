---
tags:
  Printers/Voron/2_4/Mods
  ToolBoards/EBB36
  ToolHeads/AntHead
  ToolHeads/AntHead/Mounts
  Authors/onsimon
---


Location:  https://github.com/DraftShift/StealthChanger/tree/main/UserMods/onsimon

Contained In: git

Since the extuder motor on Orbiter V2 sits quite low, the EBB36 will interfere with the optotap PCB on some toolhead backplates (Dragon Burner and Yavoth, maybe more). So I created this PCB carrier that places the EBB36 a few mm higher than other existing mounts, and also tried to make it as rigid as possible without extra structures or modifications.

Parts:

- Standoffs included with the EBB36
- 2 M3 BHCS to secure the mount against the standoffs
- 2 M3 SHCS to secure the EBB36 to the mount
- Optional: 2 M3 5x4 heat inserts (print the corresponding STL)

It is modelled to real-world dimensions and works fine as-is with ABS for me, but you can consider slicing with appropriate shrinkage compensation for your specific filament for the best possible fit.

NOTE: This DOES give enough clearance for the OptoTap!

[[EBB36]] [[Voron-2.4]] [[Micron]] [[AntHead]] 
