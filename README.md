# BMS-project
 Battery Management System for Low Voltage Low Power Domestic Equipment
📘 Final Year B.Tech Project (Electrical & Electronics Engineering)
🎓 Government Engineering College, Barton Hill  
🧑‍💻 Project Member: Jevin Johny V

## 🔋 Overview

This project presents a modular Battery Management System (BMS) for 6S Li-ion battery packs used in low-power domestic equipment such as robotic vacuum cleaners.

It includes:
- Passive cell balancing using **BQ77915 IC**
- State-of-Charge (SoC) & State-of-Health (SoH) estimation via **Modified Coulomb Counting**
- Custom-designed 2-layer PCB using **KiCad**
- Real-time monitoring and fault protection

## 🛠 Technologies Used
- **Microcontroller**: TMS320F28379D (Texas Instruments)
- **Programming**: Embedded C, MATLAB Simulink Embedded Coder
- **PCB Design**: KiCad
- **Simulation**: MATLAB Simulink
- **ICs**: BQ77915, External MOSFETs, Single-Supply Op-Amps

## ⚙️ My Role & Contributions
- 🔧 Full microcontroller setup (ADC configuration, SoC logic, interrupt-based sensing)
- 💻 Embedded C code generation from MATLAB models
- 🧩 Designed the 2-layer PCB layout (top & bottom routing)
- 📐 Hardware-level design with fault protection
- 📊 Prototype testing and debugging

## 🔍 Features
- SoC estimation via Coulomb Counting and OCV methods
- Passive balancing current up to 250 mA using external FETs
- Short-circuit, overvoltage, undervoltage, temperature fault handling
- Stackable PCB design for higher-voltage systems

## 🚀 Future Improvements
- Advanced SoH estimation algorithms
- Integration with wireless monitoring (BLE)
- Improved fault diagnosis with onboard diagnostics

---

📫 **Looking for job opportunities** in Embedded Systems or PCB Design!  
Feel free to check out the repo or connect with me on [LinkedIn](https://www.linkedin.com/in/jevinjohny).

