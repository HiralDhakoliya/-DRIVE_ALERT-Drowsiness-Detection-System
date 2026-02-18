# 👁️ DRIVE_ALERT – Drowsiness Detection System

**A research-driven smart safety system designed to monitor driver alertness and prevent road accidents caused by drowsiness.**

---

## 📌 Problem Overview

Drowsy driving is a leading cause of road accidents globally. In India alone:

- Approximately **40% of accidents** are due to drowsy driving.  
- Roughly **100,000 crashes** occur annually.  
- **71,000 injuries** and **1,550 casualties** each year.  

Lack of knowledge and the unaffordability of existing solutions prevent widespread adoption of safety systems.  

**DRIVE_ALERT** was designed to provide an **affordable, accessible lifeline** for the driver community.  

---

## 🎯 Objective

- Prevent accidents caused by drowsiness.  
- Protect the driver community from fatal consequences.  
- Prioritize affordability and accessibility for widespread adoption.  
- Minimize vision obstruction through optimized design.  

---

## 🧠 System Architecture

The system utilizes a compact hardware stack for maximum efficiency:

### Core Components

| Component | Function |
|-----------|---------|
| **ATtiny402 Microcontroller** | Central processing unit |
| **IR Sensor (STHS34PF80)** | Detects eye closing/flicker |
| **ADXL335 Accelerometer** | Monitors motion sensing |
| **Vibrating Motor** | Provides haptic feedback |
| **nRF24L01 Module** | Wireless communication output |
| **Beeper/Alarm** | Audible alert for driver |

---

## ⚙️ Working Methodology

1. **Initialization**: System powers on via a CR2032 battery and transistor system.  
2. **Monitoring**: IR sensors integrated into spectacle frames continuously track eye movement.  
3. **Detection**: The system identifies if the driver's eyes remain closed for **3 seconds or more**.  
4. **Alert Trigger**: Upon drowsiness detection, the ATtiny402 activates the vibrating motor and a loud beep.  
5. **Awakening**: Dual haptic and audible feedback ensures the driver is immediately alert.  

---

## 📊 Cost Analysis (Updated Prototype)

| Component Category | Cost (₹ INR) |
|------------------|-------------|
| Microcontroller (ATtiny402) | 35 |
| Sensors (IR & Accelerometer) | 620 |
| Communication (nRF24L01) | 120 |
| Output (Vibrator & Transistor) | 124 |
| Power (CR2032 Battery) | 8 |
| **Total Estimated Cost** | **907** |

> ✅ Reduced from ₹954 in the initial prototype, ensuring better affordability for general public use.  

---

## 🖼 Project Visuals

- **Presentation Slides:** [`assets/5129.pptx`](assets/5129.pptx)  
- **Research Poster:**[assets/Drive_alert.jpg](assets/Drive_alert.jpg)
 

---

## 🚀 Future Scope

- **Power Management:** Transitioning to a fully rechargeable battery system.  
- **Modular Design:** Detachable frame system for universal use.  
- **Enhanced Safety:** Integration with vehicle steering wheels and automated SOS system.  

---

## 🏆 Research Recognition

Presented at **Aavishkar Inter-Collegiate/Institute/Department Research Convention (UG Level)**.  

This project reflects:

- Structured problem analysis  
- System design thinking  
- Commitment to transforming road safety  

---

## 👩‍💻 Author

**Hiral Dhakoliya**  
B.Sc. Computer Science | University of Mumbai  

Focused on building **research-backed, real-world technology systems** combining engineering logic with product thinking.  

---

