---
title: All-in-one GitHub Repository
weight: 3
---

All source code and design files are available on [GitHub](https://github.com/oldrev/borneo).

## The directory structure of the Git repository

- `client/`: Mobile app source code
- `fw/`: Firmware source code
    - `scripts`: Related Python scripts, including the device Python client library
    - `cmake`: CMake scripts
    - `components`: Common ESP-IDF component source code
    - `lyfi`: LED controller firmware-related source code
    - `doser`: Dosing pump firmware-related source code (under development)
- `hw/`: Circuit design source files
    - `blc06`: 6-channel LED controller core board design
    - `blb0657f`: 6-channel 57W LED lamp aluminum PCB design
    - `3d-models`: Exported STEP format 3D models of the core boards
    - `datasheets`: The hardware specifications in PDF format
`tools/`: Related scripts and tools

