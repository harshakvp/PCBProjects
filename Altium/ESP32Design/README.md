# ESP32-S3 Custom Development Board

[![Altium Designer](https://img.shields.io/badge/EDA-Altium%20Designer-blue)](https://www.altium.com/in)
[![ESP32-S3](https://img.shields.io/badge/MCU-ESP32--S3-green)](https://www.espressif.com/)
[![Repository](https://img.shields.io/badge/Repository-ESP32Design-black)](https://github.com/harshakvp/PCBProjects/tree/main/Altium/ESP32Design)
[![GitHub](https://img.shields.io/badge/GitHub-harshakvp-181717?logo=github)](https://github.com/harshakvp)

![Top PCB View](https://github.com/harshakvp/PCBProjects/blob/cf027911819012640931e08baca7a365c565dad7/Altium/ESP32Design/Documents/My%20Files/Top%203D.png)

A custom 4-layer ESP32-S3 development board designed in Altium Designer for embedded systems development, PCB design learning, and hardware prototyping. The board features USB Type-C connectivity, USB-to-UART programming, automatic boot/reset circuitry, onboard 3.3 V regulation, and GPIO expansion headers.

---

## Overview

This project is a custom ESP32-S3 development board built around the ESP32-S3-MINI-1 module. The design follows a complete PCB development workflow including custom library creation, schematic capture, PCB layout, design verification, and generation of manufacturing-ready outputs.

### Key Functional Blocks

* ESP32-S3-MINI-1 Module
* USB Type-C Interface
* FT231XQ-R USB-to-UART Bridge
* Auto Boot & Reset Circuitry
* 3.3 V Power Regulation
* GPIO Expansion Headers
* USB ESD Protection

---

## Features

* ESP32-S3-MINI-1 MCU Module
* USB Type-C Connectivity
* FT231XQ-R USB-UART Interface
* Automatic Boot and Reset Circuit
* 4-Layer PCB Design
* Onboard 3.3 V LDO Regulation
* USB ESD Protection
* GPIO Expansion Headers
* Manufacturing-Ready Design Files

---

## PCB Design

### Schematic

![Schematic](https://github.com/harshakvp/PCBProjects/blob/cf027911819012640931e08baca7a365c565dad7/Altium/ESP32Design/Documents/My%20Files/Schematics.jpg)

### Layer 1 – Top Layer

Primary component placement and signal routing layer.

![Layer 1](https://github.com/harshakvp/PCBProjects/blob/cf027911819012640931e08baca7a365c565dad7/Altium/ESP32Design/Documents/My%20Files/Layer%201.png)

### Layer 2 – Power Routing Layer

Dedicated layer for routing power signals and distributing supply rails across the board.

![Layer 2](https://github.com/harshakvp/PCBProjects/blob/cf027911819012640931e08baca7a365c565dad7/Altium/ESP32Design/Documents/My%20Files/Layer%202.png)

### Layer 3 – Ground Plane

Continuous ground reference plane for improved signal integrity, reduced EMI, and reliable return current paths.

![Layer 3](https://github.com/harshakvp/PCBProjects/blob/cf027911819012640931e08baca7a365c565dad7/Altium/ESP32Design/Documents/My%20Files/Layer%203.png)

### Layer 4 – Bottom Layer

Additional signal routing layer and component interconnections.

![Layer 4](https://github.com/harshakvp/PCBProjects/blob/cf027911819012640931e08baca7a365c565dad7/Altium/ESP32Design/Documents/My%20Files/Layer%204.png)

---

## Repository Structure

```text
ESP32Design/
│
├── Documents/
│   ├── Datasheets
│   ├── Reference Schematics
│   └── Design Documents
│
├── Project Outputs for ESP32Design/
│   ├── BOM/
│   ├── Gerber/
│   ├── NC Drill/
│   ├── Pick Place/
│   └── Send To Production/
│
├── ESP32Design.PrjPcb
├── ESP32Design.SchDoc
├── ESP32Designv1.1.PcbDoc
├── SchLib.SchLib
├── PCBLib.PcbLib
└── Job.OutJob
```

### Folder Description

| Folder/File            | Description                                                                   |
| ---------------------- | ----------------------------------------------------------------------------- |
| Documents              | Datasheets, reference schematics, and supporting design documents             |
| Project Outputs        | Manufacturing outputs including Gerbers, BOM, drill files, and assembly files |
| ESP32Design.SchDoc     | Main schematic design                                                         |
| ESP32Designv1.1.PcbDoc | PCB layout                                                                    |
| SchLib.SchLib          | Custom schematic symbol library                                               |
| PCBLib.PcbLib          | Custom PCB footprint library                                                  |
| ESP32Design.PrjPcb     | Altium project file                                                           |
| Job.OutJob             | Output job configuration                                                      |

---

## Getting Started

### Clone Repository

```bash
git clone https://github.com/harshakvp/PCBProjects.git
```

### Navigate to the Project

```bash
cd PCBProjects/Altium/ESP32Design
```

### Open in Altium Designer

```text
ESP32Design.PrjPcb
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
Project Outputs for ESP32Design/
```

This directory contains:

* Gerber Files
* NC Drill Files
* Bill of Materials (BOM)
* Pick-and-Place Files
* Assembly Outputs

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

* GitHub: https://github.com/harshakvp
* LinkedIn: https://www.linkedin.com/in/harshakvp/
* Portfolio: [https://www.harshakvp.dev](https://chain-science-5eb.notion.site/HARSHAK-V-P-4f4889ae8ebf4c05a5790637c39213ba)
* Email: harshakvp.contact@gmail.com

Feel free to open an issue, submit improvements, or reach out regarding the project.
