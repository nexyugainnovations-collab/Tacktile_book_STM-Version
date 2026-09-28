# Tacktile Book STM (v1.0)

STM32-based hardware design for the Tacktile book, an interactive tactile book that plays audio in response to touch. This repository contains the PCB design files and the audio content used by the device.

Developed by **Nexyuga Innovations**.

## Contents

| Folder | Description |
|--------|-------------|
| pcb/ | Schematic and board layout source files |
| gerber/ | Fabrication outputs (Gerbers, drill files) |
| bom/ | Bill of materials |
| audio/ | Audio files used by the device |
| docs/ | Datasheets, notes and images |

Folder names may differ slightly from the actual layout. Update the table to match the repository.

## Hardware

- **Microcontroller:** STM32 (part number: TBD)
- **PCB design tool:** TBD
- **Audio:** stored audio played back through an amplifier and speaker
- **Input:** touch or button input from the tactile pages

## Getting Started

Clone the repository:

    git clone https://github.com/nexyugainnovations-collab/Tacktile_book_STM-Version.git
    cd Tacktile_book_STM-Version

1. Open the project file from the pcb/ folder in your PCB design tool.
2. To manufacture the board, send the contents of gerber/ to a PCB fabricator and use bom/ for component sourcing.
3. Flash the firmware to the STM32 using STM32CubeProgrammer or an ST-Link.

## Version History

| Version | Notes |
|---------|-------|
| v1.0 | Initial release: PCB and audio files |

## Contributors

- Pravin Balu ([*****](https://github.com/*****))
- Nithilan Saravanan ([@nithilan0710](https://github.com/nithilan0710))
- Nexyuga Innovations

## License

Proprietary. All rights reserved by Nexyuga Innovations.
