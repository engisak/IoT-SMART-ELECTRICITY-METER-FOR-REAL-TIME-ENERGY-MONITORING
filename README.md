# ⚡ IoT-Based Smart Electricity Meter for Real-Time Energy Monitoring and Efficiency Management  

![IoT](https://img.shields.io/badge/Project-IoT-blue)  
![Status](https://img.shields.io/badge/Status-Completed-success)  
![License](https://img.shields.io/badge/License-Academic-green)  
![Platform](https://img.shields.io/badge/Platform-Blynk%20App%20%7C%20ESP32-orange)  

---

## 📖 Overview  
This project implements an **IoT-based smart electricity meter** that enables **real-time monitoring, smart alerts, and remote load control**.  
The system uses the **ESP32 microcontroller** with **current and voltage sensors** to measure energy consumption and send data to both an **OLED display** and the **Blynk mobile app** for remote monitoring.  

The solution helps users:  
- Reduce **energy wastage**  
- Track **electricity usage**  
- Receive **notifications** when consumption exceeds limits  
- Remotely control electrical loads  

---

## 🎯 Project Objectives  
1. **Real-Time Monitoring** – Provide users with instant access to energy usage data.  
2. **Visual Data Display** – Show live readings on OLED and mobile app.  
3. **Smart Alerts** – Notify users when usage exceeds a predefined threshold.  
4. **Remote Load Control** – Allow ON/OFF control of devices via relay module.  

---

## ⚙️ Features  
- 📊 **Live Monitoring** of voltage, current, power usage.  
- 🔔 **Consumption Alerts** when monthly limits are reached.  
- 📱 **Remote Control** of electrical devices through Blynk.  
- ⚡ **Accurate Readings** (±2% compared to standard multimeter).  
- 🔄 **Scalable Design** for homes, offices, and industries.  

---

## 🛠️ System Components  
- **ESP32 Microcontroller**  
- **ACS712 Current Sensor**  
- **ZMPT101B Voltage Sensor**  
- **4-Channel Relay Module**  
- **OLED Display (0.96")**  
- **Buzzer & LED Indicators**  
- **Blynk IoT Platform**  

---

## 📐 System Architecture  
```text
[ Current Sensor ] --->  
[ Voltage Sensor ] ---> [ ESP32 Microcontroller ] ---> OLED Display  
                                                ---> Blynk App (Mobile)  
                                                ---> Relay Module ---> Electrical Loads  
## 📊 Comparative Analysis  

The table below compares the **Proposed IoT-Based Smart Electricity Meter** with **Traditional Manual Meters** and **Existing IoT Meters** based on key performance metrics and features.

| Criteria / Feature                | Traditional Manual Meter | Existing IoT Meters       | Proposed System (This Project) |
|-----------------------------------|--------------------------|---------------------------|---------------------------------|
| **Real-Time Monitoring**          | ❌ No                    | ✅ Yes                    | ✅ Yes (OLED & Mobile App)     |
| **Remote Access**                  | ❌ No                    | ✅ Limited                | ✅ Full (Anywhere via Blynk)   |
| **Automatic Alerts**               | ❌ No                    | ✅ Yes                    | ✅ Smart threshold-based alerts|
| **Remote Load Control**            | ❌ No                    | ❌ No                     | ✅ Yes (4-channel relay)       |
| **Energy Usage Limit Notification**| ❌ No                    | ❌ No                     | ✅ Yes                         |
| **Data Accuracy**                  | Low (~±10%)              | Moderate (~±5%)           | High (±2% vs Multimeter)       |
| **Ease of Use**                    | Easy                     | Moderate                  | Very Easy (User-friendly UI)   |
| **Scalability**                    | ❌ Low                   | ✅ Medium                 | ✅ High                        |
| **Internet Independence**          | ✅ Yes                   | ❌ No                     | ✅ Partial (basic offline display) |

---

**Key Improvements in the Proposed System:**
1. **Higher accuracy** (±2%) compared to both manual and existing IoT meters.  
2. **Integrated alert system** for consumption limits.  
3. **Remote load control**, allowing users to turn devices ON/OFF from anywhere.  
4. **User-friendly interface** with both OLED local display and Blynk app for remote monitoring.  
5. **Scalable and adaptable** to different environments (homes, offices, shops).  

