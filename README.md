# DIP_EE3180
E022 | Project Title: **Design and Implementation of Grid-Forming Inverter System**

This is a **partial release** of the work done on our 3-phase grid-forming inverter (GFMI) project, assigned to us and developed as part of a core module project at NTU EEE.


> Due to academic and institutional confidentiality, most files (particularly: hardware + DSP source code), as well as the final report, will **not** be shared. 

## Overview 
An inverter is an electrical device that converts from Direct Current (DC) to Alternating Current (AC). Without an inverter, renewable energy sources such as photovoltaic (PV) cells cannot power most devices. 

GFMIs, like the one in this project, are specifically designed to regulate its own voltage and frequency. This allows them to operate independently or integrate seamlessly with the power grid. 

GFMIs are especially important for: 
- Better integration of renewable energy into existing power grids 
- Off-grid renewable systems/Remote islands or rural electrification 
- Backup systems during grid outages 

## Team Contributions 
This **9-person project** was largely split between 2 teams: 

**Software Team:**
- **Focus:** modelling, simulating and implementing of inverter control strategies in both islanded and grid-connected modes 
- hardware-software integration 
- Tech/Tools: `PLECS`, `MATLAB/Simulink`, `TI C2000 DSP` 

**Hardware Team:**
- **Focus:** designing and assembling the actual hardware system  
- LCL filter design and simulation 
- Tech/Tools: `LTspice`, `KiCad`, `Altium Designer`

Special thanks to the guidance of the PHD student attached to us, not only because but especially due to the high voltage nature of this project. 

## Technical Notes 
A PLECS license is needed to run the simulations in PLECS.
A MATLAB GUI can also be found in this repository. 

## Potential Future Work 
- Improve overcurrent protection on the TI C2000
- Further improve on control algorithms used in the project 
- Further reduce harmonics in the output AC 

## Final Notes 
This repository is intended for **portfolio and educational purposes only**. 
