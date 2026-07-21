# Quadratic Boost Converter PCB Redesign

[![Altium Designer](https://img.shields.io/badge/EDA-Altium%20Designer-blue)](https://www.altium.com/in)
[![DC-DC Converter](https://img.shields.io/badge/Converter-Quadratic%20Boost-green)]()
[![Repository](https://img.shields.io/badge/Repository-QuadraticConverter-black)](https://github.com/harshakvp/PCBProjects/tree/main/Altium/QuadraticConverter)
[![GitHub](https://img.shields.io/badge/GitHub-harshakvp-181717?logo=github)](https://github.com/harshakvp)

![Top PCB View](https://github.com/harshakvp/PCBProjects/blob/529d7998ede972f7e693472f4ff4d3f21b32c9d1/Altium/QuadraticConverter/Documents/Figures/3D%20View.png)

A PCB redesign of the **Quadratic Boost Converter** presented in the IEEE paper **"Analysis, Design and Experimental Verification of a Quadratic Boost Converter."** This project was developed in **Altium Designer** as a power electronics PCB design learning project, focusing on schematic capture, custom library creation, PCB layout, design verification, and generation of manufacturing-ready outputs.

> **Note**
>
> This project is a PCB implementation of the converter presented in the referenced publication and is intended solely for educational purposes, PCB design practice, and hardware prototyping.

---

## Overview

This project is a PCB implementation of the Quadratic Boost Converter proposed by **K. Tattiwong** and **C. Bunlaksananusorn**. The original converter is a high step-up non-isolated DC-DC converter employing a single active switch and two cascaded boost stages to achieve a quadratic voltage gain.

The objective of this project is to gain practical experience in power electronics PCB design by translating the published converter into a manufacturable PCB using Altium Designer while following industry-standard design practices.

Unlike the original implementation, which employs a UC3825 PWM controller for closed-loop voltage regulation, this PCB provides an **external PWM input header** that allows the converter to be driven by a microcontroller, function generator, or other PWM source. This approach simplifies experimental validation while providing greater flexibility for future controller development.

### Design Specifications

| Parameter | Value |
|-----------|-------|
| Input Voltage | 12 V |
| Output Voltage | 48 V |
| Output Power | 100 W |
| Switching Frequency | 100 kHz |
| Converter Topology | Quadratic Boost Converter |
| PCB Layers | 2 |
| EDA Software | Altium Designer |

---

## Key Functional Blocks

- External PWM Input Header
- TC4420 High-Speed MOSFET Gate Driver
- IRF3710 Power MOSFET
- Quadratic Boost Power Stage
- Input & Output Connectors
- Passive Energy Storage Components
- Test Points for Electrical Measurements

---

## Features

- PCB Redesign of a Published IEEE Quadratic Boost Converter
- Designed using Altium Designer
- External PWM Input Interface
- TC4420 High-Speed MOSFET Gate Driver
- IRF3710 Power MOSFET
- Through-Hole Power Components
- Clearly Labeled Test Points
- 2-Layer PCB Design
- Manufacturing-Ready Design Files

---

## PCB Design

### Schematic

![Schematic](https://github.com/harshakvp/PCBProjects/blob/f4079e0340e5ac003d500fe7ddc5525b93674afc/Altium/QuadraticConverter/Documents/Figures/Schematics.jpg)

---

### Top Layer

Primary component placement and high-current power routing.

![Top Layer](https://github.com/harshakvp/PCBProjects/blob/f4079e0340e5ac003d500fe7ddc5525b93674afc/Altium/QuadraticConverter/Documents/Figures/Top%20Layer.png)

---

### Bottom Layer

Additional routing layer and ground interconnections.

![Bottom Layer](https://github.com/harshakvp/PCBProjects/blob/f4079e0340e5ac003d500fe7ddc5525b93674afc/Altium/QuadraticConverter/Documents/Figures/Bottom%20Layer.png)

---

### 3D View

Complete PCB assembly visualization.

![3D View](https://github.com/harshakvp/PCBProjects/blob/f4079e0340e5ac003d500fe7ddc5525b93674afc/Altium/QuadraticConverter/Documents/Figures/Top%203D%20View.png)

---

## Repository Structure

```text
QuadraticConverter/
│
├── Documents/
│   ├── Datasheets/
│   ├── Draw.io/
│   ├── Figures/
│   ├── Reference Components/
│   └── Reference Papers/
│
├── Project Outputs for QuadraticConverter/
│   ├── BOM/
│   ├── Gerber/
│   ├── NC Drill/
│   ├── Reports/
│   └── Send To Production/
│
├── QuadraticConverter.PrjPcb
├── QuadraticConverter.SchDoc
├── QuadraticConverter.PcbDoc
├── QuadraticConverter.SchLib
├── QuadraticConverter.PcbLib
└── Job.OutJob
```

### Folder Description

| Folder/File | Description |
|-------------|-------------|
| Documents | Datasheets, reference papers, figures, and supporting design documents |
| Project Outputs | Manufacturing outputs including Gerbers, BOM, drill files, reports, and production package |
| QuadraticConverter.SchDoc | Main converter schematic |
| QuadraticConverter.PcbDoc | PCB layout |
| QuadraticConverter.SchLib | Custom schematic symbol library |
| QuadraticConverter.PcbLib | Custom PCB footprint library |
| QuadraticConverter.PrjPcb | Altium project file |
| Job.OutJob | Output job configuration |

---

## Getting Started

### Clone Repository

```bash
git clone https://github.com/harshakvp/PCBProjects.git
```

### Navigate to the Project

```bash
cd PCBProjects/Altium/QuadraticConverter
```

### Open in Altium Designer

```text
QuadraticConverter.PrjPcb
```

1. Launch Altium Designer.
2. Open the project file.
3. Compile the project.
4. Review the schematic and PCB layout.
5. Generate manufacturing outputs if required.

---

## Manufacturing Files

Ready-to-manufacture files are available under:

```text
Project Outputs for QuadraticConverter/
```

This directory contains:

- Gerber Files
- NC Drill Files
- Bill of Materials (BOM)
- Design Reports
- Production Package

---

## Project Workflow

```text
Reference Paper
        │
        ▼
Component Selection
        │
        ▼
Custom Library Creation
        │
        ▼
Schematic Capture
        │
        ▼
PCB Layout
        │
        ▼
Design Rule Check (DRC)
        │
        ▼
Gerber & NC Drill Generation
        │
        ▼
PCB Manufacturing
        │
        ▼
Manual Assembly
```

---

## Reference

This PCB redesign is based on the following publication:

**K. Tattiwong** and **C. Bunlaksananusorn**

**Analysis, Design and Experimental Verification of a Quadratic Boost Converter**

Proceedings of **TENCON 2014 - IEEE Region 10 Conference**

**DOI:** https://doi.org/10.1109/TENCON.2014.7022467

---

## License

This project is released as open-source hardware for educational, learning, and prototyping purposes.

You are free to:

- Study the design
- Modify the design
- Manufacture the PCB
- Use it in personal, academic, or research projects

---

## Author

### Harshak V P

Electrical and Electronics Engineering Undergraduate

Vellore Institute of Technology (VIT), Vellore

#### Areas of Interest

- Power Electronics
- Embedded Systems
- Electric Drives
- PCB Design
- Power Converter Design
- Machine Learning Applications in Engineering

---

## Connect

- GitHub: https://github.com/harshakvp
- LinkedIn: https://www.linkedin.com/in/harshakvp/
- Portfolio: https://chain-science-5eb.notion.site/HARSHAK-V-P-4f4889ae8ebf4c05a5790637c39213ba
- Email: harshakvp.contact@gmail.com

Feel free to open an issue, submit improvements, or reach out regarding the project.
