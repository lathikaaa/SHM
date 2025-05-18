# SHM
Structural Health Monitoring

## 🏗️ Structural Health Monitoring System – Python Simulation

### 📌 **Project Overview**

This project simulates a **Structural Health Monitoring (SHM)** system using Python. It mimics how sensors installed on key parts of a structure (e.g., beams and columns) collect data on **vibrations, strain, and temperature** to detect potential structural issues.

The primary goal is to demonstrate how real-time monitoring can help in **early detection of stress or damage**, thereby enhancing safety and reliability in buildings, bridges, and other civil infrastructure.

---

### ⚙️ **Key Features**

* Simulates sensors at different structural locations (e.g., Beam 1, Column B).
* Randomly generates realistic sensor data:

  * **Acceleration** (0–10 m/s²)
  * **Strain** (1000–3000 microstrain)
  * **Temperature** (20–80 °C)
* Compares each reading against predefined **safety thresholds**.
* Issues **alerts** if readings exceed thresholds (e.g., excessive vibration or overheating).
* Performs the simulation over multiple monitoring cycles.
* Uses `time.sleep()` to simulate real-time data acquisition.

---

### 🧠 **Use Cases**

* Ideal for educational purposes, prototyping, or explaining SHM principles.
* Can be expanded to support real sensor input, GUI dashboards, or cloud storage.
* Provides a foundation for developing real-world IoT or civil engineering monitoring systems.

---

### 🔧 **Future Enhancements (Optional Ideas)**

* Real-time plotting of sensor data.
* Data logging to a file or database.
* Email or SMS alerts.
* Basic anomaly detection using AI.
* Interactive GUI dashboard with live status indicators.



