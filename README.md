# XRUN Monitor

3rd-party ReaPack repository. 

XRUN Monitor detects XRUNs by measuring drift between the software audio clock
and OS clock.

## Overview
- XRUNs are detected by JSFX and written to REAPER GMEM
- Lua actions can:
  - Create project regions at XRUN positions
  - Export XRUNs to CSV
  - Insert empty space in project to compensate for drift (experimental)

## Author
Håvard Endresen (HAST3)
