# Filterless Cross-Connected Multilevel Inverter (CC-MLI) with SHE-PWM
 
M.Sc. thesis project (DUET, 2019–2025) — design, simulation, and hardware implementation of a filterless Cross-Connected Multilevel Inverter using Selective Harmonic Elimination (SHE) modulation.
 
## Overview
Multilevel inverters reduce total harmonic distortion (THD) and switching losses compared to conventional two-level inverters, but typically require output filters to meet power-quality standards. This project develops a **filterless CC-MLI topology**, using SHE-PWM to minimize THD directly at the switching stage — in line with IEEE 519 recommended practice — removing the need for bulky passive filtering.
 
## Contents
- `simulink/` — MATLAB/Simulink models: switching logic, fault-scenario simulation, output waveform and THD analysis
- `hardware/` — PCB design files, gate-drive schematics (IGBT/MOSFET switching stage)
- `docs/` — thesis excerpts, SHE angle calculation methodology, published paper reference
## Methodology
1. Topology design — cross-connected multilevel architecture, filterless output stage
2. SHE-PWM switching angle computation for target harmonic elimination
3. Simulink modelling — validated switching logic, fault behaviour, and output power quality
4. Hardware prototyping — full-cycle PCB layout, IGBT/MOSFET gate-drive and protection circuit design
5. Bench validation against simulation results
## Publication
M. Mustakim, M. Z. Hossain, M. J. Ferdous, "Cross-Connected Multi Level Multi Input Inverter for Low Harmonics Operation," *12th IEEE International Conference on Electrical and Computer Engineering (ICECE)*, Dhaka, Bangladesh, 2022, pp. 392–396.
DOI: [10.1109/ICECE57408.2022.10088702](https://doi.org/10.1109/ICECE57408.2022.10088702)
 
## Supervisor
Prof. Dr. Md. Zakir Hossain, Dept. of EEE, DUET
 
## Status
Thesis complete; repository being populated with cleaned-up simulation and design files.
 
## Author
Mohammad Mustakim — mustakimm.engr.eee@gmail.com
