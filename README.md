# Aerodel – Advanced Delivery Drone System

## Short Description
A lightweight delivery drone prototype capable of carrying a **500 g payload**. Features ultrasonic obstacle avoidance, GPS integration, and a failsafe landing mechanism to enhance navigation accuracy and flight safety.

---

## Key Features
- **Payload Capacity:** Up to 500 g  
- **Collision Avoidance:** Ultrasonic sensors detect obstacles for safe navigation  
- **Precision Navigation:** GPS-based positioning  
- **Failsafe Landing:** Ensures safe touchdown during signal loss  
- **Performance:** Improved navigation accuracy by 25% compared to baseline  
- **Safety Enhancement:** Failsafe system reduced crash risk during tests  

---

## Tech Stack
- **Hardware:** ESP32, Ultrasonic sensors, LiPo battery, Flight controller (KK 2.1.5 or similar)  
- **Firmware:** ESP-IDF, Embedded C, FreeRTOS  
- **Tools:** Git/GitHub, Markdown documentation  

---

## Setup & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/MelvinJoshua27/Aerodel-Drone-Delivery-System.git
   cd Aerodel-Drone-Delivery-System
2. Navigate to the firmware and hardware folders for component details.
3. Follow hardware schematics to assemble the drone.
4. Flash firmware onto your ESP32 using ESP-IDF.
5. Power up the drone and conduct short-range test flights in controlled environments.
---

## Results
In controlled flight tests:
- Navigation accuracy improved by 25%
- Failsafe mechanism activated successfully, significantly reducing crash incidents

---

## Folder Structure
- hardware/ – Schematics, components list, wiring diagrams
- firmware/ – Source code for sensors, failsafe logic, GPS integration
- docs/ – Documentation, setup instructions, testing results
- media/ – Photos and demo footage of the prototype in action

---

## Future Enhancements
- Integration with LoRa for extended-range SLAM
- Implementation of real-time mapping capabilities
- Miniaturization of hardware components for portability
- Integration of LiFi-based communication for secure data transfer
---
