<p align="center">
  <img src="assets/header.svg" alt="Ajeeth Venkat Prasat, Embedded Systems Engineer: biomedical wearables, IoT edge devices, signal processing, edge AI" width="100%">
</p>

<p align="center">
  <a href="https://ajeethv27.github.io"><img src="https://img.shields.io/badge/Portfolio-ajeethv27.github.io-06B6D4?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio website"></a>
  <a href="https://www.linkedin.com/in/ajeethv"><img src="https://img.shields.io/badge/LinkedIn-ajeethv-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ajeethvp@gmail.com"><img src="https://img.shields.io/badge/Email-ajeethvp%40gmail.com-0E1A2B?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://ajeethv27.github.io/Ajeeth_Venkat_Prasat_Engineering_Portfolio.pdf"><img src="https://img.shields.io/badge/Portfolio-PDF-C2410C?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Portfolio PDF"></a>
</p>

### Hi, I'm Ajeeth 👋

I build embedded systems that sit close to the physical world: sensors that produce awkward signals, the analog electronics that make those signals usable and the firmware + machine learning that turn them into decisions. I have three years of experience across industry (**Cognizant**) and applied research (**Fraunhofer EMI**, **livMatS**), and hold an M.Sc. in Embedded Systems Engineering from the **University of Freiburg**.

```c
struct Engineer ajeeth = {
    .role       = "Embedded Systems Engineer",
    .based_in   = "Freiburg, Germany",
    .focus      = { "biomedical wearables", "IoT edge devices",
                    "real-time signal processing", "edge AI / TinyML" },
    .latest     = "Self-powered TENG insole for gait analysis: 93.58 % accuracy",
    .languages  = { "English (C1)", "German (B1)", "Hindi (B2)", "Tamil" },
    .status     = OPEN_TO_EMBEDDED_ROLES,
};
```

---

### 🔬 Featured work

<table>
  <tr>
    <td width="50%"><a href="https://github.com/ajeethv27/teng-gait-wearable"><img src="assets/card_teng.svg" alt="Self-powered gait-analysis insole: 93.58% activity accuracy"></a></td>
    <td width="50%"><a href="https://ajeethv27.github.io/#rover"><img src="assets/card_rover.svg" alt="Autonomous sensor-fusion rover: 95% autonomous navigation"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://ajeethv27.github.io/#waste"><img src="assets/card_waste.svg" alt="Smart waste monitoring with TinyML: 40% faster facility response"></a></td>
    <td width="50%"><a href="https://github.com/ajeethv27/iot-sewage-monitoring"><img src="assets/card_sewage.svg" alt="IoT sewage monitoring system"></a></td>
  </tr>
</table>

<details>
<summary><b>More about the flagship project: the TENG gait insole</b></summary>
<br>

A triboelectric nanogenerator (TENG) in the heel of a shoe insole turns every footstep into an electrical signal, so the sensor needs no battery. A custom **AD795 electrometer front-end** reads the GΩ-impedance source without loading it, an **ESP32** digitises it, and an **XGBoost** model on FFT features classifies standing, walking, running and jumping.

| Metric | Result |
|---|---|
| Accuracy (4 activities, 122,652 test windows) | **93.58 %** |
| Macro F1-score | **0.94** |
| Study | 12 participants · 84 recordings |
| TENG output | ≈ 800 mV open-circuit · 10.58 µW peak |

→ [Project write-up](https://github.com/ajeethv27/teng-gait-wearable) · [Analysis code](https://github.com/ajeethv27/Gait_Analysis_Project) · Paper under review at *IEEE Sensors Journal*
</details>

**Also built:** AI fall detection (IMU + LSTM for elderly care) · Automated car parking (CAN bus, Python, Raspberry Pi)

---

### 🧰 Toolbox

**Languages**<br>
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Embedded & systems**<br>
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-3F8F3F?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![ROS](https://img.shields.io/badge/ROS-22314E?style=flat-square&logo=ros&logoColor=white)

**AI / ML**<br>
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TinyML](https://img.shields.io/badge/TinyML-0E7490?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Hardware & protocols**<br>
![OrCAD](https://img.shields.io/badge/OrCAD-PCB-B22222?style=flat-square)
![Altium](https://img.shields.io/badge/Altium-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white)
![Analog front-ends](https://img.shields.io/badge/Analog-signal%20conditioning-0E1A2B?style=flat-square)
![Protocols](https://img.shields.io/badge/CAN%20·%20SPI%20·%20UART%20·%20I²C-334155?style=flat-square)
![Wireless](https://img.shields.io/badge/BLE%20·%20Wi--Fi%20·%20MQTT%20·%20LoRaWAN-334155?style=flat-square)

**Tools**<br>
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

---

### 🧭 Path so far

| When | Role | Where |
|---|---|---|
| 2024 – 2025 | **Master's thesis:** biomedical wearable for rehabilitation | livMatS · University of Freiburg |
| 2024 | **Student research assistant:** robotics & sensor systems | Fraunhofer EMI, Freiburg |
| 2023 – 2024 | **Start-up project:** TinyML smart waste monitoring | Hahn-Schickard / Uni Freiburg |
| 2022 – 2026 | **M.Sc. Embedded Systems Engineering** | University of Freiburg |
| 2021 – 2022 | **Software engineer:** test automation & healthcare analytics | Cognizant, Bengaluru |
| 2019 | **Graduate innovation engineer:** IoT energy monitoring | Forge Innovation & Ventures |
| 2017 – 2021 | **B.E. Electrical & Electronics Engineering** | Anna University (Kumaraguru College of Technology) |

### 📄 Publications

- **Intelligent Biomedical Wearable for Gait Analysis in Rehabilitation**, *IEEE Sensors Journal* (under review)
- **Energy Management System for Smart Factories**, *IRJET*, Vol. 7, Issue 9, 2020, pp. 3390–3393

---

<p align="center">
  <sub>Open to embedded systems roles in Germany. The quickest way to reach me is <a href="mailto:ajeethvp@gmail.com">email</a> or <a href="https://www.linkedin.com/in/ajeethv">LinkedIn</a>.</sub>
</p>
