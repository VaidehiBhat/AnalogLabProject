# Transmitter–Antenna Power Amplifier Design using BJT Topologies

This project involves the design and implementation of a multi-stage BJT-based amplifier to interface a low-power transmitter with a 300 Ω antenna. The system boosts a **1 mW signal** to **120 mW output power** while maintaining signal integrity.

## 🛠️ Problem Statement

> Design an amplifier circuit that enables a **1 mW signal at 200 kHz** to be transmitted through a **300 Ω antenna** by boosting it to **120 mW**, while ensuring proper voltage/current gain and impedance matching.  
>  
> Analyze the amplifier's input/output impedances, waveform characteristics, and gain–bandwidth response.

---

## 🧠 Project Summary

- **Input Signal**: 1 V RMS (1 mW power)
- **Output Requirement**: 8.41 V, 20 mA (120 mW power)
- **Target Gain**: Voltage Gain = 6
- **Topology Used**:
  - Voltage gain stage: Common Emitter Amplifier
  - Current boosting stages: Emitter Followers (unity gain)
  - Biasing: Voltage divider bias for stability
- **Impedance Matching**: Tuned for efficient power transfer to 300 Ω antenna

---

## 🔧 Methodology

1. **Stage 1**: Designed a BJT common-emitter amplifier to achieve required voltage gain.
2. **Stage 2**: Implemented multiple emitter follower stages to boost current without distorting the signal.
3. **Calculated and verified**: 
   - Input/output power  
   - RMS voltages and currents  
   - Output waveform quality  
   - Frequency response and bandwidth

---

## 📁 Repository Contents

- `report.pdf` — Complete report with explanation, methodology, calculations, waveforms, and results  
- `schematic.png` — Schematic of the final amplifier design  
- `README.md` — This file  

---

## 🔍 Key Results

- **Output Power Achieved**: 117.6 mW  
- **Waveform**: Clean sinusoidal output at 8.41 V (RMS)  
- **Impedance Matching**: Verified via Rout/Rin calculations  
- **Frequency Response**: Plotted and bandwidth measured  
- **Power Transfer Efficiency**: Maximized through proper topology selection and staging



## ✅ Conclusion

The amplifier circuit successfully boosted the transmitter signal to meet the antenna requirements with minimal distortion. Careful selection of BJT topologies and impedance matching ensured stable and efficient operation.

---

