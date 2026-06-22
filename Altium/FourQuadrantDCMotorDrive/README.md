# Four Quadrant DC Motor Drive

[![Altium Designer](https://img.shields.io/badge/EDA-Altium%20Designer-blue)](https://www.altium.com/in)
![IR2110](https://img.shields.io/badge/Gate%20Driver-IR2110-green)
![IRFZ44N](https://img.shields.io/badge/MOSFET-IRFZ44N-orange)
[![Repository](https://img.shields.io/badge/Repository-FourQuadrantDCMotorDrive-black)](https://github.com/harshakvp/PCBProjects/tree/main/Altium/FourQuadrantDCMotorDrive)
[![GitHub](https://img.shields.io/badge/GitHub-harshakvp-181717?logo=github)](https://github.com/harshakvp)

![3D View](https://github.com/harshakvp/PCBProjects/blob/cc99e24477105a9991b268a048be75901a3c5528/Altium/FourQuadrantDCMotorDrive/Documents/Figures/3D%20View.png)

A custom two-layer DC motor drive PCB designed in Altium Designer for motor control and power electronics applications. The design implements a MOSFET H-Bridge topology with IR2110 gate drivers, enabling four-quadrant motor operation including forward motoring, reverse motoring, and dynamic braking.

---

## Overview

This project is a custom DC motor drive board developed to explore power electronics hardware design, gate driver integration, PCB layout practices, and manufacturing-ready design generation. The design includes a high-current MOSFET H-Bridge, gate driver circuitry, control interfaces, and braking functionality.

### Key Functional Blocks

* MOSFET H-Bridge Power Stage
* IR2110 High and Low Side Gate Drivers
* PWM Motor Speed Control
* Direction Control Interface
* Dynamic Braking Circuit
* Power Input and Motor Output Interfaces

---

## Features

| Feature           | Description                                         |
| ----------------- | --------------------------------------------------- |
| Topology          | Four-Quadrant DC Motor Drive                        |
| Power Stage       | MOSFET H-Bridge                                     |
| Gate Driver       | IR2110 High and Low Side Driver                     |
| Motor Control     | PWM-Based Speed Control                             |
| Direction Control | Forward and Reverse Operation                       |
| Braking Method    | Dynamic Braking Circuit                             |
| PCB Layers        | 2-Layer PCB                                         |
| Design Tool       | Altium Designer                                     |
| Libraries         | Custom Schematic Symbols and PCB Footprints         |
| Outputs           | Gerbers, NC Drill Files, BOM, and Assembly Drawings |

---

## PCB Design

### Schematic

![Schematic](https://github.com/harshakvp/PCBProjects/blob/cc99e24477105a9991b268a048be75901a3c5528/Altium/FourQuadrantDCMotorDrive/Documents/Figures/Schematics.jpg)

### Top Layer

Primary component placement and signal routing layer.

![Top Layer](https://github.com/harshakvp/PCBProjects/blob/cc99e24477105a9991b268a048be75901a3c5528/Altium/FourQuadrantDCMotorDrive/Documents/Figures/Top%20Layer.png)

### Bottom Layer

Signal routing and return current paths.

![Bottom Layer](https://github.com/harshakvp/PCBProjects/blob/cc99e24477105a9991b268a048be75901a3c5528/Altium/FourQuadrantDCMotorDrive/Documents/Figures/Bottom%20Layer.png)

### Top & Bottom View

Combined board view showing overall routing and component placement.

![Top & Bottom View](https://github.com/harshakvp/PCBProjects/blob/cc99e24477105a9991b268a048be75901a3c5528/Altium/FourQuadrantDCMotorDrive/Documents/Figures/Top%20%26%20Bottom%20Layer.png)

### 3D View

Complete assembled board visualization.

![3D View](https://github.com/harshakvp/PCBProjects/blob/cc99e24477105a9991b268a048be75901a3c5528/Altium/FourQuadrantDCMotorDrive/Documents/Figures/3D%20View.png)

---

## PCB Stackup

| Layer        | Description                            |
| ------------ | -------------------------------------- |
| Top Layer    | Component Placement and Signal Routing |
| Bottom Layer | Signal Routing and Ground Return Paths |

---

## Repository Structure

```text
FourQuadrantDCMotorDrive/
│
├── Documents/
│   ├── Figures
│   ├── Footprints
│   ├── 3D Models
│   ├── Schematics.pdf
│   └── Assembly Drawings.pdf
│
├── Project Outputs for FourQuadrantDCMotorDrive/
│   ├── BOM/
│   ├── Gerber/
│   └── NC Drill/
│
├── FourQuadrantDCMotorDrive.PrjPcb
├── FQDMDSchematic.SchDoc
├── FQDMDPCBv1.1.PcbDoc
├── FQDMDSchematicLibrary.SchLib
├── FQDMDPCBLibrary.PcbLib
└── Job1.OutJob
```

### Folder Description

| Folder/File                     | Description                                                   |
| ------------------------------- | ------------------------------------------------------------- |
| Documents                       | Design documents, figures, footprints, and 3D models          |
| Project Outputs                 | Manufacturing outputs including Gerbers, BOM, and drill files |
| FQDMDSchematic.SchDoc           | Main schematic design                                         |
| FQDMDPCBv1.1.PcbDoc             | PCB layout                                                    |
| FQDMDSchematicLibrary.SchLib    | Custom schematic symbol library                               |
| FQDMDPCBLibrary.PcbLib          | Custom PCB footprint library                                  |
| FourQuadrantDCMotorDrive.PrjPcb | Altium project file                                           |
| Job1.OutJob                     | Output job configuration                                      |

---

## Getting Started

### Clone Repository

```bash
git clone https://github.com/harshakvp/PCBProjects.git
```

### Navigate to the Project

```bash
cd PCBProjects/Altium/FourQuadrantDCMotorDrive
```

### Open in Altium Designer

```text
FourQuadrantDCMotorDrive.PrjPcb
```

1. Launch Altium Designer.
2. Open the project file shown above.
3. Compile the project.
4. Review the schematic and PCB layout.
5. Generate manufacturing outputs if required.

---

## Manufacturing Files

Ready-to-manufacture files are available under:

```text
Project Outputs for FourQuadrantDCMotorDrive/
```

This directory contains:

* Gerber Files
* NC Drill Files
* Bill of Materials (BOM)
* Assembly Drawings

---

## License

This project is released as open-source hardware for educational, learning, and prototyping purposes.

You are free to:

* Study the design
* Modify the design
* Manufacture the PCB
* Use it in personal, academic, or research projects

---

## Author

### Harshak V P

Electrical and Electronics Engineering Undergraduate
Vellore Institute of Technology (VIT), Vellore

#### Areas of Interest

* Embedded Systems
* Power Electronics
* Electric Drives
* PCB Design
* IoT Systems
* Machine Learning Applications in Engineering

#### Connect

* GitHub: [harshakvp](https://github.com/harshakvp)
* LinkedIn: [Harshak V P](https://www.linkedin.com/in/harshakvp/)
* Portfolio: [harshakvp.dev](https://chain-science-5eb.notion.site/HARSHAK-V-P-4f4889ae8ebf4c05a5790637c39213ba)
* Email: [harshakvp.contact@gmail.com](mailto:harshakvp.contact@gmail.com)

Feel free to open an issue, submit improvements, or reach out regarding the project.
