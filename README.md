# microphone-preamplifier
 Low-Noise Microphone Preamplifier
# 🧪 Advanced Electronics/Analog System Project: Low-Noise Battery-Powered Microphone Preamplifier

📅 **Degree**: M.S. in Electrical and Computer Engineering
📅 **Course**: Advanced Electronics
🏫 **Instructor**: Prof. Gary Saulnier
🛠 **Tool**: LTspice
📄 **Report**: [Final Report (PDF)](Report/Saroj_Design_Project.pdf)

---

## 🎯 Objective

Design and simulate a **low-noise microphone preamplifier** for battery-powered applications with the following goals:

* Amplify low-level mic signals with minimal noise
* Maintain flat audio-band frequency response (20 Hz – 15 kHz)
* Achieve long battery life from ±1.5 V supply (2× AAA batteries)
* Meet constraints on harmonic distortion, cost, and power draw

---

## ⚙️ Design Summary

* **Input Stage**: LSK170A JFET for low-noise, high input impedance
* **Op-Amp**: AD8605 rail-to-rail, low-power op-amp
* **Topology**: AC-coupled non-inverting amplifier
* **Key Components**:

  * Rf, Rg for gain control
  * C4 to roll off high-frequency noise

---

## 📊 Results Summary

| Metric                | Requirement    | Achieved   |
| --------------------- | -------------- | ---------- |
| Frequency Range       | 20 Hz – 15 kHz | ✅ Yes      |
| Max Output Swing      | > 1 Vpp        | ✅ 2.4 Vpp  |
| Signal-to-Noise Ratio | > 90 dB        | ⚠️ ~88 dB  |
| Avg Current Draw      | < 2 mA         | ✅ ~1.22 mA |
| Battery Life Estimate | > 600 hrs      | ✅ ~975 hrs |
| Cost                  | Minimized      | ✅ ~$13.50  |

---

## 🔬 Simulation & Validation

* **AC Sweep** → Flat midband gain across 20 Hz–15 kHz
* **Transient Analysis** → Undistorted output with 2.4 Vpp swing
* **Noise Analysis** → ~36.6 μV RMS input-referred noise
* **FFT** → Low harmonic content, strong dynamic range

📁 See plots in `/Plots/` and schematic in `/LTspice_Circuits/`

---

## 📂 File Structure

```
├── LTspice_Circuits/  	 # .asc schematic files
├── Plots/  			 # AC/Noise/FFT screenshots
├── Report/
│   └── Saroj_Design_Project.pdf
├── README.md
```

---

## 📫 Contact

**Saroj Shah**
📍 Albany, NY 12208
📞 [+1 (617) 955-5843](tel:+16179555843)<br>
📧 [engsarojshah@gmail.com](mailto:engsarojshah@gmail.com)<br>
🔗 [LinkedIn](https://linkedin.com/in/sarojkshah)<br>
🌐 [Portfolio](https://drsarojshah.github.io)<br>

---

> 🔧 This project highlights practical analog design, simulation-based validation, and low-noise optimization suitable for audio a
