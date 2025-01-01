
# IoT-Based Smart Home Automation 

This project simulates a home automation system using the Picsimlab simulator and the Blynk IoT mobile application. The system enables the control of garden lights, temperature, and water tank levels, with real-time monitoring and automation features.

---

## Features

### **1. Garden Lights Control**  
- **Input:** LDR sensor.  
- **Functionality:** Adjusts LED brightness based on sunlight availability, simulating garden light control.  
- **Output:** LED brightness control.  

### **2. Temperature Control System**  
- **Input:** LM35 temperature sensor.  
- **Functionality:**  
  - Displays temperature on CLCD and Blynk gauge widget.  
  - Controls heater and cooler via Blynk button widgets.  
  - Turns off the heater automatically if the temperature exceeds 35°C and notifies the user.  
- **Output:** Temperature display and device control.  

### **3. Water Tank Control**  
- **Input:** Serial tank data.  
- **Functionality:**  
  - Monitors water volume and displays it on the CLCD and Blynk gauge widget.  
  - Controls inlet and outlet valves via Blynk button widgets.  
  - Automatically disables the inlet valve and sends notifications when the tank is full.  
- **Output:** Water volume monitoring and valve control.  

---

## Tools Used

- **Simulator:** Picsimlab  
- **IoT Application:** Blynk  
- **Hardware Simulation:** Arduino components  
- **Dashboard:** CLCD for real-time event monitoring  

---

## User Interface

- **Blynk Widgets:**  
  - Button Widgets: Control heater, cooler, and inlet/outlet valves.  
  - Gauge Widgets: Display temperature and water volume.  
  - Terminal Widgets: Display notifications, e.g., "Temperature exceeds 35°C," "Water level full."  

---

## How to Use

1. **Setup the Simulation Environment:**  
   - Use Picsimlab for Arduino simulation.  
   - Install the Blynk mobile app for IoT control.

2. **Create Widgets in Blynk:**  
   - Add button widgets for heater, cooler, and valve controls.  
   - Add gauge widgets for temperature and water level display.

3. **Run the Simulation:**  
   - Configure the components (LEDs, sensors, valves) in Picsimlab.  
   - Monitor and control devices via the Blynk app.

---

## Functional Overview

### **Threshold Controls:**  
- Heater turns off when the temperature exceeds 35°C, displaying a message on CLCD and Blynk terminal.  
- Inlet valve turns off automatically when the water tank is full, with notifications displayed on CLCD and Blynk terminal.  

### **Real-Time Monitoring:**  
- CLCD serves as a dashboard for event visualization.  
- Blynk widgets provide remote control and status updates.  

