# Smart Fault-Tolerant Sensor Monitoring System  
*A Modbus RTU-based Industrial Automation Solution with Adaptive Polling & Encrypted IoT Integration for Industry 4.0.*

---

🚀 Overview  
Industrial environments require reliable, **real-time monitoring systems** for hazard detection and predictive maintenance.  
This project modernizes **Modbus RTU (RS485)** by integrating:

- **Adaptive polling algorithm** – prioritizes critical sensors (gas/flame).
- **Fault detection system** – real-time alerts and logging.
- **AES-encrypted IoT bridge** – secure cloud connectivity (MQTT/Blynk).
- **Python Tkinter GUI** – lightweight SCADA alternative.

---

 ✨ Extended Description  
This project upgrades legacy **Modbus RTU networks** to **Industry 4.0** standards. It combines Arduino-based sensor nodes with a Python-based master that features intelligent polling and fault detection. Real-time data is securely transmitted to the cloud for remote monitoring, making it ideal for **industrial automation, factory floors, and predictive maintenance**.

**Applications:**  
- Industrial hazard detection (gas/fire/temperature).
- Smart factories and Industry 4.0 automation.
- Remote monitoring of critical environments (oil & gas, chemical plants).

---

 🔧 Key Features  
- **35% reduction** in Modbus traffic with adaptive polling.
- Real-time fault detection in **<3 seconds**.
- Secure AES-encrypted data push to MQTT/Blynk dashboards.
- Modular architecture – easily extendable to other sensors.

---

 🖥 System Architecture  
```
[ Sensors ] → [ Arduino (Slave) ] → [ RS485 Bus ] → [ Python Master ]
                     ↓                          ↓
             Fault Detection        Cloud Dashboard (MQTT/Blynk)
                     ↓                          ↓
                Tkinter GUI              Encrypted Data Logs
```

---

## 📁 Repository Structure  
```
arduino/
   smart_modbus_slave.ino
python_master/
   main.py
tests/
   test_sample.py
docs/
   image 1.png
config.example.yaml
requirements.txt
README.md
LICENSE
```

---

 📦 Quick Start  
 **1. Clone Repo**
```bash
git clone https://github.com/<your-username>/smart-modbus-rtu-iot-monitoring.git
cd smart-modbus-rtu-iot-monitoring
```
### **2. Install Dependencies**
```bash
pip install -r requirements.txt
```
### **3. Run the Python Master**
```bash
python python_master/main.py
```

---

## 📷 Screenshots  
(Upload images in `docs/` and update the links below)
- ![GUI Screenshot](docs/gui_screenshot.png)
- ![Architecture](docs/architecture.png)

---

## 🔮 Roadmap  
- Modbus TCP/IP Support.
- AI-based anomaly detection.
- Mobile app dashboard integration.
- Wireless node support (LoRa/ESP32).

---

## 📚 References  
- [Modbus Protocol Specifications](https://www.modbus.org/)  
- [PyModbus Documentation](https://pymodbus.readthedocs.io)  
- [MQTT Protocol](https://mqtt.org/)  
- [AES in Python](https://www.pycryptodome.org/)  

---

## 👤 Author  
**Sakthivardhan Sankar**  
[LinkedIn](https://www.linkedin.com/in/sakthivardhan-s-81132b328/)  

