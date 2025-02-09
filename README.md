# **Smart Water Meter**  

## **Project Overview**  
This project is a **Smart Water Meter** designed for real-time water consumption monitoring. It features an **MSP430FR60431 microcontroller**, BLE/Wireless M-Bus communication, an EEPROM for data storage, and an LCD display. The PCB layout is optimized for a **100mm x 100mm** board.

---

## **Features**  
- **High-precision water flow measurement** using ultrasonic sensing.  
- **Wireless connectivity** via BLE and Wireless M-Bus.  
- **Low power consumption** with MSP430FR60431.  
- **Real-time display** on a segment LCD.  
- **Data logging** with an EEPROM/NOR Flash.  
- **Expandable I/O** for additional sensors or modules.  

---

## **Hardware Components**  

### **Microcontroller & Processing**
- **MSP430FR60431IPNR** – Low-power microcontroller optimized for ultrasonic water metering.

### **Connectivity**
- **BLE (Bluetooth Low Energy) module**  
- **Wireless M-Bus (WM-BUS) module**  

### **Memory & Storage**
- **I2C EEPROM** – Stores device configurations and logs.  
- **EEPROM/NOR Flash** – Additional storage for data logging.  

### **Display & Interface**
- **Segment LCD** – Real-time display of water usage and status.  

### **Power Management**
- **Power Module** – Voltage regulation and power management.  

### **Clock Sources**
- **8MHz Crystal** – System clock for accurate timing.  
- **32.768kHz Crystal** – Real-time clock for low-power operation.  

### **Passive Components**
- **Capacitors:**  
  - 1uF, 100nF, 10uF, 12pF, 33uF, 1000pF  
- **Resistors:**  
  - 22Ω, 10KΩ, 330KΩ, 100KΩ  
- **Inductor:**  
  - L_0603  

### **Debugging & Expansion**
- **2-Wire JTAG** – For firmware development and debugging.  
- **IO Expander (IO EXP)** – Allows adding more peripherals.  
- **Test Points** – For debugging and testing signals.  

---

## **PCB Design Details**  
- **Software Used:** EasyEDA  
- **Board Dimensions:** 100mm x 100mm  
- **Layers:**  
  - Top Layer (Red)  
  - Bottom Layer (Blue)  
  - Silkscreen (Yellow)  
  - **Routing:** Optimized for minimal signal interference  
- **Mounting Holes:** Provided for secure enclosure integration

This layout was created using EasyEDA
  
![Screenshot (74)](https://github.com/user-attachments/assets/b69a2068-eaf5-4368-92a4-ce94ca3be6d9)
---

## **Installation & Usage**  
1. **Assembly:** Solder components according to the PCB layout.  
2. **Firmware Upload:** Use JTAG to flash firmware onto MSP430.  
3. **Power On:** Connect to power supply or battery.  
4. **Wireless Setup:** Configure BLE/Wireless M-Bus.  
5. **Monitor Data:** Use an LCD display or mobile app to view readings.  

---

## **Future Improvements**  
- Integration with **AI/ML** for anomaly detection.  
- Addition of **LoRaWAN** for long-range connectivity.  
- **Solar-powered** operation for sustainable deployment.  

---

