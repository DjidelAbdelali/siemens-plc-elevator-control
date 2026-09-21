# Siemens PLC Sequential Elevator Controller

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Interactive-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://djidelabdelali.github.io/siemens-plc-elevator-control/)
[![Portfolio](https://img.shields.io/badge/Portfolio-DJIDEL%20Abdelali%20Rayan-blue?style=for-the-badge&logo=react&logoColor=white)](https://djidelabdelali.github.io/portfolio/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DjidelAbdelali/siemens-plc-elevator-control)

</div>

---

## 📌 Project Overview

Sequential elevator control system programmed and simulated using Siemens PLC automation logic (Ladder Diagram, Grafcet, STL). Features multi-floor request handling and safety interlocking.

This project is an engineering module built by **DJIDEL Abdelali Rayan** (Systems & Automation Engineer, USTHB).

---

## 🏗️ System Architecture & Data Flow

```mermaid
graph TD
    Buttons[Floor Call Buttons & Limit Sensors] --> Grafcet[Grafcet / Sequential State Machine]
    Grafcet --> S71200[Siemens S7-1200 PLC Controller]
    S71200 --> VFD[VFD Motor Drive & Door Actuators]
    VFD --> Cabin[Elevator Cabin Position State]
```

---

## 🛠️ Key Technologies & Frameworks

- **Siemens PLC**
- **Ladder Diagram**
- **Grafcet**
- **STL Logic**
- **Industrial Automation**

---

## 🚀 Live Interactive Web Demo

No installation required! Test and interact with the full web simulation live in your browser:
🔗 **[Launch Interactive Web Demo](https://djidelabdelali.github.io/siemens-plc-elevator-control/)**

---

## 🔗 Connected Portfolio Ecosystem

- 🌐 **Main Portfolio**: [djidelabdelali.github.io/portfolio](https://djidelabdelali.github.io/portfolio/)
- 💻 **GitHub Profile**: [github.com/DjidelAbdelali](https://github.com/DjidelAbdelali)
- 💼 **LinkedIn Profile**: [DJIDEL Abdelali Rayan](https://linkedin.com/in/djidel-abdelali-rayan-814b25207)

---

<div align="center">
  <sub>Developed by DJIDEL Abdelali Rayan — Systems & Automation Engineering</sub>
</div>
