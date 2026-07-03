# Data-Driven Adaptive Cruise Control for Trucks with Lane-Keeping Assistance

Replication and extension of the IEEE Transactions on Vehicular Technology paper using pure MATLAB/Simulink.

## Project Overview

This project implements a **data-driven Adaptive Cruise Control (ACC)** system for heavy-duty trucks, integrated with a **Lane-Keeping Assistance (LKA)** module. The vehicle dynamics are modeled using a 5-DOF (Degree of Freedom) truck plant with Magic Formula tire modeling.

## Directory Structure

```
Data-Driven_ACC_for_Trucks_with_LKA/
├── models/          # Simulink models (.slx files)
├── scripts/         # MATLAB scripts (data generation, AI training, utilities)
├── data/            # Datasets (CSV, MAT files for training/validation)
├── docs/            # Documentation, reference papers, and notes
├── .gitignore
└── README.md
```

## Key Components

- **5-DOF Truck Plant Model** — longitudinal, lateral, yaw, and wheel dynamics
- **Magic Formula Tire Model** — nonlinear tire force computation (Pacejka)
- **Data-Driven ACC Controller** — AI/ML-based adaptive cruise control
- **Lane-Keeping Assistance** — lateral path-tracking controller

## Tools & Dependencies

- MATLAB R2024a+ (or compatible)
- Simulink
- (Optional) Deep Learning Toolbox / Reinforcement Learning Toolbox

## Status

🚧 **Work in Progress** — Currently building the 5-DOF plant model and tire subsystems.

## License

This project is for academic and research purposes.
