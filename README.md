# Two-Stage Amplifier — Cadence Simulation

This project demonstrates the design and simulation of a **two-stage amplifier** using **Cadence Virtuoso**.  
The design combines a **differential amplifier** (first stage) with **current mirror biasing** and a **common-source MOSFET amplifier** (second stage) also biased with a current mirror for improved gain and stability.

---

## 📌 Key Highlights

- **✅ Differential Amplifier (Stage 1)**  
  Designed a differential pair as the first stage for differential-mode gain and common-mode rejection, with an active current mirror as the tail current source for stable biasing.

- **✅ Common-Source Amplifier (Stage 2)**  
  Implemented a common-source MOSFET amplifier as the second gain stage to boost overall gain, also biased using a current mirrorconnected to the tail current source of the differential amplifier to ensure proper operating point and high output swing.

- **✅ Cascaded Gain**  
  Connected both stages to achieve higher overall voltage gain while preserving the benefits of differential input.

- **✅ AC Analysis**  
  Performed frequency-domain simulations to observe the combined **magnitude gain vs. frequency** and **phase response**, verifying midband gain and -3dB bandwidth.

- **✅ Transient Analysis**  
  Simulated time-domain waveforms to confirm correct amplification, phase shift, and signal swing through both stages.

- **✅ Key Metrics Observed**
  - Total voltage gain of the cascaded amplifier
  - Phase margin and frequency response
  - Input/output swing
 
This project demonstrates how multiple amplifier stages can be combined with active current mirrors to design high-gain analog circuits with good bias stability.

---

## 🧰 Tools Used

- **Cadence Virtuoso** (schematic design and simulation)
- **Spectre / ADE** for AC and transient analysis

---

## 📁 Files


- Waveform screenshots




