# PCB Design Project using KiCad

## Overview
This project focuses on designing a Printed Circuit Board (PCB) using KiCad, an open-source Electronic Design Automation (EDA) software. The project includes schematic creation, component placement, routing, and PCB layout generation.

The goal of this project is to understand the complete PCB design workflow from concept to fabrication-ready files.

---

## Features
- Schematic design using KiCad
- Component footprint assignment
- PCB layout design
- Track routing and optimization
- Design Rule Check (DRC)
- 3D PCB visualization
- Gerber file generation for manufacturing

---

## Tools Used
- **Software:** KiCad
- **Version Control:** Git & GitHub
- **PCB Type:** Single-layer / Double-layer
- **Output Files:** Gerber, Drill, BOM

---

## Project Workflow

### 1. Schematic Design
Created the circuit schematic by selecting and connecting electronic components.

### 2. Footprint Assignment
Assigned PCB footprints for all components.

### 3. PCB Layout
Imported the schematic into PCB editor and arranged components efficiently.

### 4. Routing
Connected all tracks while minimizing interference and optimizing space.

### 5. Design Rule Check
Verified the design for errors and rule violations.

### 6. 3D Visualization
Reviewed the final PCB in 3D for better understanding.

### 7. Gerber Generation
Generated manufacturing files for PCB fabrication.

---

## Folder Structure

```bash
PCB-Design-KiCad/
│── schematic/
│   ├── project.kicad_sch
│
│── pcb/
│   ├── project.kicad_pcb
│
│── gerber/
│   ├── *.gbr
│
│── images/
│   ├── schematic.png
│   ├── pcb-layout.png
│   ├── 3d-view.png
│
│── README.md