# 134.2 kHz RFID Reader (EM4095 + ESP32)

> Designed and built as a hands-on hardware project to understand low-frequency RFID systems.

---

## 🔧 Features
- Operates at 134.2 kHz (LF RFID)
- Custom-designed PCB with integrated coil antenna
- EM4095 RFID analog front-end
- ESP32 for data processing and communication

---

## 🧠 Working Principle
The coil antenna generates a magnetic field at 134.2 kHz.  
When an RFID tag enters the field, it modulates the signal.  
This modulated signal is detected and demodulated by the EM4095.  
The ESP32 reads and processes the decoded data.

---

## 📷 Project Images

### PCB Layout
![PCB](images/Screenshot%202026-03-31%20210803.png)

### 3D View
![3D](images/Screenshot%202026-03-31%20210818.png)

### Schematic
![Schematic](images/Screenshot%202026-03-31%20210833.png)

---

## 🛠️ Hardware Used
- EM4095 RFID IC  
- ESP32  
- Custom PCB coil antenna  

---

## 📂 Project Structure

- `hardware/` → PCB design, antenna, and hardware-related files  
- `software/` → ESP32 code  
- `images/` → project visuals  

---

## 📦 Hardware Details

- `antenna_134.2kHz/` → Coil antenna design files  
- `pcb_coils/` → Coil design variations and experiments  
- `EM4095/` → Reference circuits and IC-related files  

---

## 📋 Bill of Materials (BOM)

The complete list of components used in this project is available here:

`hardware/BOM/rfid_reader_bom.csv`

### Key Components
- EM4095 RFID IC  
- ESP32  
- Capacitors (100nF, tuning capacitors)  
- Resistors  
- Coil antenna  

---

## ▶️ How to Use

1. Open hardware files using KiCad  
2. Upload ESP32 code using Arduino IDE  
3. Power the circuit and monitor output via serial  

---

## ⚠️ Improvements / Future Work
- Improve coil tuning for better resonance  
- Enhance signal filtering for stability  
- Increase read range and reliability  

---

## 🚀 Applications
- Animal tracking systems  
- Access control  
- Identification systems  

---

## 📌 Status
Project completed and tested.

---

## 🤝 Contributions
This is a personal learning project. Suggestions and improvements are welcome.
