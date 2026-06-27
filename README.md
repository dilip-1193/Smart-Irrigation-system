# 🌱 Smart Irrigation System using Cisco Packet Tracer

## 📖 Project Overview

This project presents an **IoT-based Smart Irrigation System** developed using **Cisco Packet Tracer 9.0.0**. The system is designed to optimize water usage in agricultural fields by monitoring environmental conditions and automatically controlling irrigation through lawn sprinklers.

The solution integrates cloud computing, networking infrastructure, IoT devices, and edge computing to demonstrate an automated irrigation system capable of reducing water wastage while improving irrigation efficiency.

---

# 🎯 Aim

To design and simulate an IoT-enabled Smart Irrigation System using Cisco Packet Tracer that monitors environmental conditions and automatically controls irrigation based on predefined conditions, thereby optimizing water usage in agricultural fields.

---

# ❗ Problem Statement

Traditional irrigation systems generally operate manually or follow fixed schedules without considering the actual environmental conditions. This often leads to excessive water consumption, inefficient irrigation, and increased operational costs.

The objective of this project is to develop a smart irrigation system capable of monitoring humidity and water level in real time and automatically activating irrigation only when required. The system also supports remote monitoring through IoT technologies.

---

# 📌 Scope of the Solution

The proposed solution is capable of:

- Monitoring humidity in the agricultural field.
- Monitoring water level continuously.
- Automatically controlling lawn sprinklers.
- Providing wireless communication between IoT devices.
- Supporting remote monitoring through a laptop.
- Demonstrating IoT automation using Cisco Packet Tracer.

### Future Enhancements

- Soil Moisture Sensor integration
- Weather forecast integration
- Mobile application support
- AI-based irrigation scheduling
- Cloud data analytics
- SMS and Email notifications

---

# 🏗 System Architecture

The Smart Irrigation System consists of two major sections:

## Cloud Computing Layer

- Cloud
- Cisco 2811 Router
- Cisco 2960 Switch
- DNS Server
- IoT Server

## Edge Computing Layer

- Home Gateway
- Laptop
- Humiture Monitor
- Water Level Monitor
- Three Lawn Sprinklers

The Home Gateway acts as the central IoT controller by collecting sensor information, executing automation rules, and controlling the sprinklers.

---

# ⚙ Working Principle

1. The Humiture Monitor continuously measures the humidity of the agricultural field.
2. The Water Level Monitor monitors the available water level.
3. Both sensor readings are transmitted wirelessly to the Home Gateway.
4. The Home Gateway evaluates the configured automation rules.
5. If irrigation is required, the Home Gateway activates the lawn sprinklers.
6. Once sufficient water level or humidity is available, the sprinklers are automatically turned OFF.
7. The Laptop provides real-time monitoring of sensor values, sprinkler status, and IoT devices.

---

# 🖥 Components Used

## Networking Devices

- Cloud-PT
- Cisco 2811 Router
- Cisco 2960 Switch
- Cable Modem
- Home Gateway (DLC100)
- DNS Server
- IoT Server
- Laptop
- Smartphone
- Cell Tower
- Central Office Server

## IoT Devices

- Humiture Monitor
- Water Level Monitor
- Lawn Sprinkler ×3

## Communication Media

- Copper Straight Through Cable
- Coaxial Cable
- Wireless IoT Communication

## Software

- Cisco Packet Tracer 9.0.0

---

# 📋 Function of Each Component

| Component | Function |
|-----------|----------|
| Smartphone | Enables remote monitoring of the irrigation system over the Internet. |
| Cell Tower | Provides wireless communication between the smartphone and the Central Office Server. |
| Central Office Server | Simulates the ISP and forwards Internet traffic. |
| Cloud | Represents Internet connectivity between the remote network and agricultural field. |
| Cisco Router | Routes packets between cloud services and the local network. |
| Cisco Switch | Connects all wired network devices within the local network. |
| DNS Server | Resolves domain names into IP addresses. |
| IoT Server | Registers and manages IoT devices and automation services. |
| Cable Modem | Connects the Home Gateway to the Internet. |
| Home Gateway | Acts as the IoT controller by executing automation rules and managing IoT devices. |
| Laptop | Used to monitor IoT devices and configure automation rules. |
| Humiture Monitor | Measures environmental humidity. |
| Water Level Monitor | Monitors water level for irrigation decisions. |
| Lawn Sprinklers | Automatically irrigate the agricultural field when activated. |

---

# 🤖 Automation Rules

## Rule 1 – Smart Irrigation ON

### Conditions

- Water Level < 30 cm
- Humidity < 40%

### Actions

- Turn ON Lawn Sprinkler 1
- Turn ON Lawn Sprinkler 2
- Turn ON Lawn Sprinkler 3

---

## Rule 2 – Smart Irrigation OFF

### Conditions

- Water Level ≥ 30 cm
- OR Humidity ≥ 40%

### Actions

- Turn OFF Lawn Sprinkler 1
- Turn OFF Lawn Sprinkler 2
- Turn OFF Lawn Sprinkler 3

---

# 📷 Simulated Circuit

The logical topology consists of:

- Cloud Computing Layer
- Networking Infrastructure
- IoT Server
- Home Gateway
- Laptop
- Humiture Monitor
- Water Level Monitor
- Three Lawn Sprinklers

> **Insert the screenshot of the completed logical topology here.**

---

# ▶ Execution / Demo

The demonstration video includes:

- Complete system overview
- Explanation of networking components
- Explanation of IoT devices
- Home Gateway configuration
- IoT Dashboard demonstration
- Automation rule configuration
- Real-time monitoring of sensor values
- Automatic sprinkler control

---


---

# 💻 Software Requirements

- Cisco Packet Tracer 9.0.0
- GitHub

---

# 📊 Results

The Smart Irrigation System was successfully designed and simulated using Cisco Packet Tracer. The Home Gateway successfully manages the IoT devices, monitors environmental conditions, and controls the lawn sprinklers according to predefined automation rules. The system demonstrates efficient irrigation management using IoT technology and networking concepts.

---

# ✅ Conclusion

This project successfully demonstrates the implementation of an IoT-based Smart Irrigation System capable of monitoring environmental conditions and automating irrigation. By integrating networking devices, IoT sensors, cloud connectivity, and automation rules, the system improves water management while reducing manual intervention.

The project also demonstrates how IoT technologies can be applied in precision agriculture to support sustainable farming practices and efficient resource utilization.

---

# 👨‍💻 Author

**DILIP SESHANG TS**
VIT Vellore
B.Tech – Internet of Things (IoT)

Project: Smart Irrigation System using Cisco Packet Tracer
