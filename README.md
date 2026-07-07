# 🚗 IoT-Enabled Wireless Power Transmission for Electric Vehicles

## 📌 Overview

The **IoT-Enabled Wireless Power Transmission for Electric Vehicles** project is designed to provide a smart, efficient, and cable-free charging solution for electric vehicles (EVs). Traditional EV charging requires physical connectors, which can experience wear and tear, require regular maintenance, and may present safety concerns in certain environments. This project addresses these challenges by integrating **Wireless Power Transmission (WPT)** with the **Internet of Things (IoT)** to create an intelligent charging system.

The system wirelessly transfers electrical energy from a transmitter coil to a receiver coil using **electromagnetic induction**. An IoT module continuously monitors charging parameters such as voltage, current, battery level, charging status, temperature, and power consumption. The collected data is transmitted to a cloud platform, allowing users to monitor and control the charging process remotely through a web or mobile application.

This project demonstrates how IoT and wireless charging technologies can contribute to the future of smart transportation, intelligent parking systems, and sustainable energy management.

---

# 🎯 Objectives

* Develop a wireless charging system for electric vehicles.
* Eliminate the need for physical charging cables.
* Enable real-time monitoring using IoT technology.
* Improve charging safety and user convenience.
* Monitor battery health and charging efficiency.
* Reduce maintenance associated with wired charging systems.
* Support smart city and intelligent transportation infrastructure.

---

# ✨ Features

* ⚡ Wireless power transfer using inductive coupling
* 📡 IoT-based real-time monitoring
* 📱 Remote monitoring through mobile/web dashboard
* 🔋 Live battery percentage tracking
* 🌡️ Temperature monitoring
* ⚠️ Fault detection and alerts
* ☁️ Cloud data storage
* 📊 Energy consumption analytics
* 🔐 Secure communication between devices
* 🚘 Automatic vehicle detection

---

# 🛠️ Technologies Used

### Hardware

* ESP32 / ESP8266 Wi-Fi Module
* Arduino Uno / Nano
* Wireless Charging Transmitter Coil
* Wireless Charging Receiver Coil
* Relay Module
* Voltage Sensor
* Current Sensor (ACS712)
* Temperature Sensor (LM35 / DHT11)
* Lithium-ion Battery
* Power Supply
* Breadboard and Connecting Wires

### Software

* Arduino IDE
* Embedded C/C++
* IoT Platform (Blynk / ThingSpeak / Firebase)
* HTML
* CSS
* JavaScript
* Git & GitHub

---

# ⚙️ Working Principle

1. The transmitter coil is supplied with alternating current (AC).
2. A magnetic field is generated around the transmitter.
3. The receiver coil placed beneath the EV captures this magnetic field.
4. The induced current is converted into usable DC power.
5. The battery begins charging wirelessly.
6. IoT sensors collect charging parameters.
7. The ESP32 sends sensor data to the cloud.
8. Users monitor charging status using a mobile or web dashboard.
9. Alerts are generated if abnormal conditions are detected.
10. Charging stops automatically when the battery reaches the desired level.

---

# 🏗️ System Architecture

```
Power Supply
      │
      ▼
Wireless Transmitter Coil
      │
      ▼
Electromagnetic Field
      │
      ▼
Wireless Receiver Coil
      │
      ▼
Rectifier & Battery Charging Circuit
      │
      ▼
Electric Vehicle Battery
      │
      ▼
ESP32 / ESP8266
      │
      ▼
IoT Cloud Platform
      │
      ▼
Mobile/Web Dashboard
```

---

# 📊 Parameters Monitored

* Battery Voltage
* Charging Current
* Battery Percentage
* Temperature
* Charging Status
* Power Consumption
* Charging Time
* Efficiency
* System Health

---

# 📁 Project Structure

```
IoT-Wireless-Power-Transmission/
│
├── Arduino_Code/
│   ├── transmitter.ino
│   └── receiver.ino
│
├── Web_Dashboard/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── Circuit_Diagram/
│   └── circuit.png
│
├── Images/
│   ├── prototype.jpg
│   ├── dashboard.png
│   └── architecture.png
│
├── Documentation/
│   ├── Project_Report.pdf
│   └── Presentation.pdf
│
├── LICENSE
└── README.md
```

---

# 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/IoT-Wireless-Power-Transmission.git
```

### Navigate to the Project Folder

```bash
cd IoT-Wireless-Power-Transmission
```

### Upload Arduino Code

* Open Arduino IDE.
* Install the ESP32 board package.
* Install required libraries.
* Upload the transmitter and receiver programs.

### Configure IoT

* Create an account on your preferred IoT platform.
* Obtain the API Key or Authentication Token.
* Update the credentials in the source code.
* Connect the ESP32 to your Wi-Fi network.

---

# 📱 Dashboard Functions

* Display battery percentage
* Display charging status
* View live voltage and current
* Temperature monitoring
* Charging history
* Power consumption graph
* Notifications and alerts
* Remote monitoring

---

# 📈 Future Enhancements

* Dynamic wireless charging while vehicles are moving
* AI-based charging optimization
* Renewable energy integration
* Solar-powered charging stations
* Vehicle-to-Grid (V2G) support
* Automatic parking alignment for charging
* Machine learning-based predictive maintenance
* Fast wireless charging technology

---

# 🌍 Applications

* Electric Cars
* Electric Buses
* Autonomous Vehicles
* Smart Parking Systems
* Public Charging Stations
* Industrial Electric Vehicles
* Smart Cities
* University Campuses

---

# ✅ Advantages

* No physical charging cables
* Improved safety
* User-friendly operation
* Reduced maintenance costs
* Smart monitoring
* Higher reliability
* Better charging efficiency
* Supports sustainable transportation

---

# ⚠️ Limitations

* Higher initial installation cost
* Lower efficiency than wired charging over larger distances
* Coil alignment is important
* Limited charging range
* Electromagnetic interference must be minimized

---

# 📚 References

1. IEEE Xplore Digital Library
2. International Journal of Electrical Engineering
3. Arduino Documentation
4. ESP32 Documentation
5. ThingSpeak Documentation
6. Blynk IoT Platform
7. Wireless Power Consortium (Qi Standard)

---

# 👩‍💻 Author

**Nisha Subramani**

* 🎓 B.E. Electronics and Communication Engineering
* 💻 Aspiring Software Developer
* ☕ Java Developer
* 📊 Data Analytics Enthusiast
* 🚀 Passionate about IoT, Embedded Systems, AI, and Smart Technologies

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

# 📄 License

This project is licensed under the MIT License.

---

# ⭐ Support

If you found this project useful, please consider giving it a **⭐ Star** on GitHub. Your support motivates future improvements and helps others discover the project.

Thank you for visiting this repository! 🚗⚡
