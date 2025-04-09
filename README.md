# Microstrip Line Design and Analysis

> This project presents the design and simulation of a 20 cm microstrip transmission line optimized for 50-ohm impedance. Using Keysight ADS, LineCalc, and Ansys HFSS, the analysis covers S-parameters, insertion loss, and signal integrity at multi-GHz frequencies.

---

### 📌 **Project Overview**
- **Objective:** Design a microstrip line for high-speed digital signals, ensuring impedance control and minimal loss over 20 GHz.
- **Methodology:** Designed the geometry using LineCalc and simulated impedance and S-parameters in ADS. Eye diagrams and PRBS signal transmission were validated up to 10 Gbps. HFSS was used to model radiation effects.

---

### 💡 **Key Features**
- 50-ohm matched line over 20 cm length  
- Insertion loss <1.5 dB up to 20 GHz  
- S11, S21, eye diagram, and VSWR validated  
- TX-Line used to determine substrate and trace width  

---

### 🧰 **Skills Used**
RF Design, Impedance Matching, Signal Integrity, Transmission Line Modeling

---

### 🧪 **Technologies & Tools**
Keysight ADS, TX-Line, LineCalc, Ansys HFSS

---

### 🔍 **Key Findings**
- Achieved <5% deviation from target impedance  
- Insertion loss consistent with theoretical expectations  
- Eye diagrams remained open at 10 Gbps, showing good integrity

---

### 🎓 **What I Learned**
- Impact of dielectric constant and trace geometry on impedance  
- How S-parameters correlate with eye diagram behavior  
- Practical limitations when designing long interconnects at high frequencies

---

### 🚀 **Future Work**
- Fabricate the microstrip on a real PCB and measure using a VNA  
- Compare HFSS simulation vs. physical data  
- Extend to coupled lines and differential pairs

---

### 📂 **Files Attached**
microstrip.ads, sparam_results.csv, hfss_3dmodel.png, eyediagram.png
