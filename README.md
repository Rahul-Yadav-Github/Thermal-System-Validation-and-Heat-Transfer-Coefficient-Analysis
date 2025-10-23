# Miniature Thermal Power Plant & Microscale Phase Change Studies

This repository contains the design files, simulation data, and documentation related to the project:

**“Miniature Thermal Power Plant: Design, Fabrication, and Phase Change Studies on Micro/Nano Textured Surfaces”**

from the **Department of Mechanical Engineering, Indian Institute of Technology Ropar**.

---

## 🧠 Overview

The project focuses on understanding and enhancing **condensation heat transfer** processes through surface engineering and setup development.

It comprises two major parts:

1. **Design and Fabrication of a Miniature Thermal Power Plant Setup**  
   - A compact experimental system replicating a power plant condenser.  
   - Enables controlled **filmwise vs. dropwise condensation** experiments under low-pressure conditions.  
   - Includes complete chamber design, data acquisition setup, and thermal analysis components.

2. **Microscale Phase Change on Nano/Micro Textured Surfaces**  
   - Investigates **dropwise condensation** on superhydrophobic and biphilic surfaces.  
   - Employs **experimental and numerical simulations** to study droplet coalescence and jumping phenomena.  
   - Aims to enhance **heat transfer coefficients** for applications in **thermal power, desalination, and electronics cooling**.

---

## ⚙️ Experimental Setup

### Condensation Chamber
- Material: **PTFE (Teflon)** block to ensure minimal heat loss.  
- Components:
  - **Copper cooling block** with embedded RTDs and thermocouples.  
  - **Plexiglass front window** for optical observation.  
  - **Vacuum and steam control ports** for pressure regulation (10–50 mbar).  
  - **Circular PTFE clamp** and **O-ring seals** for leak-proof design.

### Steam & Vacuum System
- **Electric boiler** with dual 2 kW heaters.  
- **Vacuum pump system** for removing non-condensable gases.  
- **Chiller unit** for coolant temperature control and subcooling variation.  
- **Pressure reduction valve** for precise steam regulation.

### Data Acquisition (DAQ)
- **NI-DAQ** and **Keithley DAQ** modules for temperature and pressure sensing.  
- **LabVIEW interface** for real-time data logging and steady-state validation.  
- **MATLAB post-processing** for calculating:
  - Heat flux  
  - Heat transfer coefficient  
  - Degree of subcooling  

---

## 🧪 Experimental Procedure

1. **Vacuuming:**  
   Create a vacuum in the condensation chamber to remove non-condensable gases.

2. **Steam Generation:**  
   Supply saturated steam from the boiler to the chamber at ~1.5 bar.

3. **Condensation Experiment:**  
   Control subcooling using a chiller (water/ethylene glycol mixture).  
   Measure surface and vapor temperatures using RTDs and thermocouples.

4. **Data Processing:**  
   MATLAB scripts analyze steady-state temperature data to compute heat flux and heat transfer coefficients.  
   Results are compared with **Nusselt’s theoretical correlation** for validation.

---

## 💻 Numerical Simulations

- Software: **OpenFOAM** (`interFoam` solver)  
- Simulations performed for **droplet coalescence and jumping** on hydrophobic and biphilic micro-grooved surfaces.  
- Parameters varied:
  - Groove height, width, and spacing  
  - Contact angles on ridges and grooves  
  - Droplet radius  
- Results confirm **coalescence-induced jumping** on properly designed biphilic micro-textures.

---

## 📊 Results Summary

- **Vacuum Leakage Tests:**  
  Achieved minimum pressure of **0.04 mbar** with leakage rate of **0.2 mbar/hr**.

- **Heat Flux Measurements:**  
  Higher heat flux observed on **superhydrophobic surfaces** compared to hydrophilic ones after accurate surface temperature calibration.

- **Numerical Insights:**  
  Biphilic surfaces demonstrated **droplet jumping behavior** that aids in efficient condensate removal and enhances surface renewal rate.

---

## 📘 Key Learnings

- **Dropwise condensation** significantly increases heat transfer compared to filmwise condensation.  
- **Surface texture and wettability** critically affect droplet nucleation, growth, and shedding behavior.  
- Maintaining **Cassie-Baxter stability** ensures long-term dropwise condensation performance.  
- A **well-sealed low-pressure environment** is crucial for accurate condensation experiments.

---

## 🧾 References

1. Paxson, A. (2011). *Condensation Heat Transfer on Nanoengineered Surfaces*, MIT.  
2. Emmerich, T. (2016). *Design of an Experimental Setup for Condensation at Low Pressure*, ETH Zurich.  
3. Miljkovic et al. (2012). *Condensate Growth Rates on Cassie Stable Surfaces*.  
4. Tang et al. (2021). *Superhydrophobic Surfaces for Sustained Dropwise Condensation*.  
5. Niu & Tang (2018). *Molecular Dynamics Simulation of Droplet Growth on Rough Surfaces*.

---

## 📂 Repository Structure

