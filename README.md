# 🌊 MAE 560 Project 2 – Multiphase Flow Simulation (ANSYS Fluent)

This repository contains the simulation project for **MAE 560: Applied Computational Fluid Dynamics (Fall 2023)** at Arizona State University. The focus is on **multiphase flow simulations** involving gas-liquid and liquid-liquid interactions, implemented using **ANSYS Fluent**.

## 📘 Project Overview

This project is divided into three tasks:
- **Task 1**: Gas-phase mixing in a bifurcated pipe system using methane and air.
- **Task 2**: Gravity-driven motion of liquid blobs (engine oil and mercury) down a slope.
- **Task 3**: Oscillating air-water mixture with transient mass flow rate analysis.

---

## 🛠 Tools Used

- **Simulation Software**: ANSYS Fluent (Workbench)
- **Mesh Resolution**: 0.005 m – 0.001 m
- **Time Step Sizes**: 0.01 s – 0.001 s
- **Models**: Volume of Fluid (VOF), Multiphase Flow, Transient Solver

---

## 🔬 Simulation Breakdown

### 🔹 Task 1: Gas-Phase Multiphase Flow

#### Case A: Left inlet closed
- Volume fraction plots of methane at t = 1 s and t = 2.5 s
- D-Index vs Time plot (0–7 s)

#### Case B: Fresh air injected from left inlet
- Same plots as Case A for comparison
- Velocity magnitude contour at t = 7 s
- Analysis: Fresh air reduces D-index significantly

### 🔹 Task 2: Gravity-Driven Liquid Blob Motion

#### (a) Liquid: Engine Oil
- 3D Iso-surfaces of blob at t = 0, 0.05, and 0.1 s
- Volume fraction contours on plane of symmetry
- ΔT vs velocity trend analysis

#### (b) Liquid: Mercury
- Same visualizations as above
- Notable differences due to density and viscosity

### 🔹 Task 3: Air-Water Oscillating Flow

- Custom boundary conditions to allow oscillation
- Mass flow rate of air vs time at opening A
- τ (oscillation period) identified
- Y-velocity contours at 0.25τ and 0.75τ

---

## 📈 Key Results

| Task | Highlight |
|------|-----------|
| Task 1 | Fresh air injection reduced methane concentration more effectively |
| Task 2 | Mercury blob deforms differently due to higher density |
| Task 3 | Oscillating flow modeled with accurate τ period, showing transient behavior |

---

## 📂 Repository Contents

```bash
📁 Multiphase-Flow-Project/
├── 📄 Project 2.pdf                # Final project report with figures and simulation results
├── 📄 Fluent Sim Files/           # (Optional) Include .cas/.dat/.wbpj if publicly shareable
│   ├── task1.wbpj
│   ├── task2_engine_oil.wbpj
│   ├── task2_mercury.wbpj
│   ├── task3_oscillation.wbpj
```
## 👨‍💻 Author
Pradnesh Laxman Mhatre
Graduate Student, Aerospace Engineering
Arizona State University
ASU ID: 1226479399
