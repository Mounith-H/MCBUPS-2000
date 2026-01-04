# MCBUPS-2000
An old school UPS board reverse engineering project

## Overview
This project involves reverse engineering and documenting a classic UPS (Uninterruptible Power Supply) board design. The MCBUPS-2000 provides backup power management and voltage regulation capabilities.

## Status
Still a work in progress. Schematic capture and PCB design are ongoing, with simulation files for key subsystems included.

## Project Structure

### 📁 Schematic
- **Location:** `schematic/MCBUPS/`
- KiCAD PCB design files
- Multi-sheet schematic design
- Complete circuit documentation

### 📁 Datasheets
Component datasheets including:
- **SG3524N** - PWM Control Circuit
- **LM324N** - Quad Operational Amplifier
- **HCF4098BE** - Dual Monostable Multivibrator
- **IC Pinouts** - Reference documentation

### 📁 Simulation
Circuit simulation files for key subsystems:
- `battery_level.ms14` - Battery level monitoring circuit
- `mains_control.ms14` - Mains power control logic
- `overload.ms14` - Overload protection circuit
- `sg3524.ms14` - SG3524 PWM controller simulation
- `stabilizer.ms14` - Voltage stabilizer circuit

## Features
- Battery backup management
- Voltage regulation and stabilization
- Overload protection
- Mains power monitoring
- PWM-based power conversion

## Tools Used
- **KiCAD** - Schematic capture and PCB design
- **Multisim** - Circuit simulation (`.ms14` files)

## Getting Started

### Prerequisites
- KiCAD 6.0 or later
- Multisim 14 or later (for simulations)

### Opening the Project
1. Clone this repository
2. Open `schematic/MCBUPS/MCBUPS.kicad_pro` in KiCAD
3. Simulation files can be opened in Multisim

## License
See [LICENSE](LICENSE) file for details.

## Contributing
This is a reverse engineering documentation project. Contributions for improvements, corrections, or additional documentation are welcome.
