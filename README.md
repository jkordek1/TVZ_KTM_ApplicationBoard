# TVZ_KTM_ApplicationBoard
 
[![Version](https://img.shields.io/github/v/release/jkordek1/TVZ_KTM_ApplicationBoard)](https://github.com/jkordek1/TVZ_KTM_ApplicationBoard/releases/tag/Initial)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/jkordek1/TVZ_KTM_ApplicationBoard)](https://github.com/jkordek1/TVZ_KTM_ApplicationBoard/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/jkordek1/TVZ_KTM_ApplicationBoard)](https://github.com/jkordek1/TVZ_KTM_ApplicationBoard/pulls)

Expansion board for two Nucleo 64 boards (master and slave), developed in 2022 for students studying at Zagreb university of applied sciences.
It enables quick and easy firmware development without the need of connecting different modules via breadboard and jumpers.

## Work in progress
This project is marked as work in progress and is not ready yet for a full release.

 ## Features
 - Toggle switches
 - LEDs
 - MCP2551 high-speed CAN transceiver
 - Digital I2C temperature sensor with address selection jumpers
 - UART, CAN, Parallel, analog, SPI and I2C communications between master and slave
 - Probe clips for easy oscilloscope connections
 
 ## Folder structure
    .
    ├── ...
    ├── 3d models               # 3D models of components
    ├── Images                  # Images of the project
    ├── KiCAD files             # Main KiCAD project folder
    │   ├── Datasheet           # Datasheet collection
    │   ├── jlcpcb              # jlcpcb production files
    │   ├── Graphics            # Custom graphics for PCB
    │   └── gerber              # gerber output folder
    └── ...
 
