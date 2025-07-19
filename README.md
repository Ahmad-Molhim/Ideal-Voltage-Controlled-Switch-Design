# 🔌 Ideal Voltage-Controlled Switches

This project explores the design and analysis of two voltage-controlled switches that aim to replicate the behavior of an ideal switch—zero voltage drop in the “ON” state, infinite resistance in the “OFF” state, instantaneous switching, and zero power loss.

Developed as part of the *Electronic Devices and Circuits 1 (2EI4)* course at McMaster University, the project includes simulations, physical implementations, and performance analysis of both switch designs.

---

## 📁 Project Contents

- **Switch 1 and Switch 2 Designs:**  
  Two unique configurations using p-channel and n-channel MOSFETs.

- **LTSpice Simulations:**  
  Used to model and predict circuit behavior under ideal and non-ideal conditions.

- **Waveforms Measurements:**  
  Conducted using the Analog Discovery 2 (AD2) to collect real-world data on:
  - Voltage drop
  - Leakage current
  - Power dissipation
  - Switching delay

- **Breadboard Implementation:**  
  Physical circuits were built to validate simulation results.

---

## 📊 Key Findings

- Real switches exhibit non-ideal behavior such as:
  - Voltage drop (e.g., ~24 mV)
  - Leakage current (~16.37 nA to 0.06 µA)
  - Non-zero switching time (~0.03 s to 0.0196 ms)
- Design trade-offs include simplicity vs. performance.
- Recommendations include using FGMOS for lower leakage.

---

## 🔧 Tools Used

- LTSpice
- Waveforms (AD2)
- Breadboard and discrete components
- Oscilloscope and math channels for data analysis

---

## 📚 References

1. Razaghian & Bonakdarpour (2012) – Reducing leakage current in floating-gate circuits  
2. Electronics-Tutorials.ws – MOSFET switching  
3. Mouser Datasheets – MC14007UB

---

## 👨‍🔧 Author

**Ahmad Molhim**  
McMaster University – Student ID: 400440228

---

