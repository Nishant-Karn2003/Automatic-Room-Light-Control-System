

💡 Room Light Automation System

Arduino-Based Smart Lighting using PIR & LDR

The Room Light Automation System is an embedded systems project designed to automatically control room lighting based on ambient light intensity and human presence. By combining a PIR motion sensor and an LDR (Light Dependent Resistor) with an Arduino Uno, the system ensures efficient energy usage, reduced power wastage, and enhanced user convenience.

📌 Project Objective

Automate room lighting without manual switching

Reduce electricity consumption

Improve convenience and smart home functionality

⚙️ How the System Works

PIR Sensor detects human movement in the room

LDR Sensor measures surrounding light intensity

Arduino Uno processes both sensor inputs

Relay Module switches the room light ON/OFF automatically

Logic:

✅ Dark + Motion detected → Light ON

❌ Bright environment OR No motion → Light OFF


🧰 Components Used

Arduino Uno R3

PIR Motion Sensor

LDR (Photoresistor)

SPDT Relay Module

NPN Transistor (BJT)

Diode

Resistors (10kΩ, 1kΩ)

Light Bulb / LED

9V Power Supply

Breadboard & Connecting Wires

🛠️ Circuit Description

The PIR sensor output is connected to a digital pin of Arduino

The LDR is connected in a voltage divider configuration to an analog pin

The relay module is driven using a transistor to safely control the light

Arduino logic decides the switching action based on sensor readings

🧪 Working Principle

The system continuously monitors:

Infrared radiation from the PIR sensor for motion detection

Ambient light levels using the LDR

The light turns ON only when both conditions are satisfied—darkness and human presence—ensuring energy-efficient automation.

✅ Advantages

Significant energy savings

Fully automatic operation

Cost-effective and easy to implement

Reduces manual effort

Suitable for homes, offices, corridors, and classrooms

📈 Applications

Smart homes

Offices and conference rooms

Hallways and staircases

Energy-efficient buildings

🏫 Academic Details

Institute: National Institute of Technology

Laboratory: EEIM & MPMC

Project Type: Embedded Systems / IoT

Guided By:

Dr. Subir Das (Assistant Professor, EIE)

Dr. Debanjan Acharyaa (Assistant Professor, EIE)
