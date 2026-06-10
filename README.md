# GuardianLink 🛡️

> **Atria Societal Impact Project (ASIP-038)**  
> *Real Problem, Real Solution, Real Impact.*

GuardianLink is an affordable, standalone, AI-powered safety wearable designed to bypass smartphone dependency entirely. By shifting critical compute and communication tasks directly to an on-device architecture, it provides an uncompromised safety lifeline for night-shift workers, students, and vulnerable demographics.

---

## 👥 Team Members

* **Lavanya Gowri S** (1AT24CD040)
* **Deekshitha L Prasad** (1AT24CG022)
* **Joel Arul A** (1AT24AI045)
* **Karthikeya A** (1AT24CG032)
* **Tanisha Prakash** (1AT24UE076)
* **Varshith R** (1AT24CD094)

**Faculty Guide:** Dr. Devi Kanan  
**Institution:** Atria Institute of Technology, Bengaluru  

---

## 🛠️ High-Level Core Architecture

* **Hardware Core:** Driven by an **ESP32-S3** microcontroller paired with a **SIM7080G** communication module. 
* **Edge AI Integration:** Uses an on-device **TinyML** model processing 6-axis **IMU** data to recognize true physical distress signatures while eliminating false alarms.
* **Resilient Infrastructure:** Transmits emergency telemetry over low-cost **NB-IoT/LTE-M** networks with automatic fallback to **2G GSM SMS** text alerts.
* **Guardian Dashboard:** A cloud-synchronized web center built with **React** and **Firebase** providing immediate real-time map updates during an active alert.

---

## 📂 Project Directory Structure (Coming Soon)
* `/firmware` - Core embedded code for the ESP32-S3.
* `/ML_training` - TinyML motion classification datasets and models.
* `/web_dashboard` - React/Tailwind frontend tracking architecture.
