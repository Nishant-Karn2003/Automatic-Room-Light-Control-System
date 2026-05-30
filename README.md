# 💡 Room Light Automation System

## Arduino-Based Smart Lighting using PIR & LDR

The **Room Light Automation System** is an embedded systems project designed to automatically control room lighting based on ambient light intensity and human presence.

By combining a **PIR Motion Sensor** and an **LDR (Light Dependent Resistor)** with an **Arduino Uno**, the system ensures efficient energy usage, reduced power wastage, and enhanced user convenience.

---

# 📌 Project Objective

* Automate room lighting without manual switching
* Reduce electricity consumption
* Improve convenience and smart home functionality

---

# ⚙️ How the System Works

1. **PIR Sensor** detects human movement in the room
2. **LDR Sensor** measures surrounding light intensity
3. **Arduino Uno** processes both sensor inputs
4. **Relay Module** switches the room light ON/OFF automatically

### Logic

* ✅ Dark + Motion Detected → **Light ON**
* ❌ Bright Environment OR No Motion → **Light OFF**

---

# 🧰 Components Used

| Component                     | Quantity    |
| ----------------------------- | ----------- |
| Arduino Uno R3                | 1           |
| PIR Motion Sensor             | 1           |
| LDR (Photoresistor)           | 1           |
| SPDT Relay Module             | 1           |
| NPN Transistor (BJT)          | 1           |
| Diode                         | 1           |
| Resistors (10kΩ, 1kΩ)         | As required |
| Light Bulb / LED              | 1           |
| 9V Power Supply               | 1           |
| Breadboard & Connecting Wires | As required |

---

# 🛠️ Circuit Description

* The PIR sensor output is connected to a digital pin of the Arduino
* The LDR is connected in a voltage divider configuration to an analog pin
* The relay module is driven using a transistor for safe switching operation
* Arduino logic decides the switching action based on sensor readings

---

# 🧪 Working Principle

The system continuously monitors:

* Infrared radiation from the PIR sensor for motion detection
* Ambient light levels using the LDR

The light turns ON only when both conditions are satisfied—**darkness and human presence**—ensuring energy-efficient automation.

---

# 🎥 Working Demo

[▶ Click Here to Watch the Demo](https://drive.google.com/file/d/1L0B24_ZaWocSOOqO-hqfOMSvN9_r8nAf/view?usp=sharing)

---

# ✅ Advantages

* Significant energy savings
* Fully automatic operation
* Cost-effective and easy to implement
* Reduces manual effort
* Suitable for homes, offices, corridors, and classrooms

---

# 📈 Applications

* Smart homes
* Offices and conference rooms
* Hallways and staircases
* Energy-efficient buildings

---

# 🏫 Academic Details

| Category         | Details                          |
| ---------------- | -------------------------------- |
| **Institute**    | National Institute of Technology |
| **Laboratory**   | EEIM & MPMC                      |
| **Project Type** | Embedded Systems / IoT           |

### Guided By

* Dr. Subir Das (Assistant Professor, EIE)
* Dr. Debanjan Acharyaa (Assistant Professor, EIE)

---

# 🌟 Conclusion

This project demonstrates an efficient and low-cost smart lighting solution using embedded systems and sensor-based automation. It highlights the practical implementation of IoT concepts for energy conservation and smart infrastructure development.
