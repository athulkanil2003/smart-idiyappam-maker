# 🔌 Smart IR Switch – Mini Project

This is a simple electronics-based mini project that implements an **IR-based contactless switch**, ideal for hygienic and touch-free operation. It uses an infrared sensor and basic components to turn appliances ON/OFF automatically based on proximity detection.

---

## 🧠 Project Overview

- 📋 **Objective**: To develop a low-cost, contactless switch using infrared technology.
- 💡 **Technology Used**: Analog IR sensor, transistor switching, basic LED or relay control
- 🔧 **Type**: Hardware-only mini project (no microcontroller/code)

---

## 🧰 Components Used

- IR LED and photodiode
- LM358 Op-Amp IC
- BC547 Transistor
- Resistors, Capacitors
- LED or Relay Module (for load control)
- Breadboard or PCB

---

## 🔁 Working Principle

- The IR LED continuously emits infrared light.
- When a hand/object comes close, the reflected light is picked up by the photodiode.
- This signal is amplified using an Op-Amp and used to trigger a transistor to switch ON a load (e.g., LED or appliance).
- Acts as a **contactless switch** for smart homes, COVID-safe touchless interfaces, etc.

---

## 📐 Circuit Diagram

See the circuit schematic inside the `/circuit/` folder.

![Circuit Preview](circuit/ir-circuit-diagram.png)

---

## 🖼️ Images of the Setup

Photos of the working project setup are available in the `/images/` folder.

---

## 📑 Project Report

Detailed explanation, block diagram, and component specs are available in the full report:  
📄 [`mini-project-report.pdf`](report/mini-project-report.pdf)

---

## 🧠 Future Scope

- Use with relay to control high-power appliances
- Add a timer for auto-off functionality
- Integrate with microcontrollers for smart home systems

---

## 👤 Developed By

**Athul K Anil**  
Electronics and Communication Engineering  
Viswajyothi College of Engineering and Technology  
📧 [athulkanil200331@gmail.com](mailto:athulkanil200331@gmail.com)
