# 🌞 Automatic Solar Tracker

An **Arduino UNO–based dual-axis solar tracking system** designed to automatically align a solar panel towards maximum sunlight intensity, thereby improving energy efficiency compared to static panels.

## 📌 Project Overview
This project demonstrates the use of **LDR sensors**, **servo motors**, and an **Arduino UNO** to create a cost-effective solar tracker.  
By continuously adjusting the solar panel’s orientation, the system maximizes power generation throughout the day.

## ⚡ Features
- Dual-axis solar tracking for accurate panel alignment.  
- Real-time light intensity detection using LDR sensors.  
- Automatic servo motor control for panel movement.  
- Improved energy capture efficiency over fixed solar panels.  
- Low-cost prototype built with readily available components.  

## 🛠️ Components Used
- Arduino UNO board  
- Solar panel  
- SG90 servo motors (x2)  
- LDR sensors (x4)  
- 10k resistors (for voltage divider circuits)  
- Jumper wires  
- Foam board / cardboard (panel mount)  

## 🔧 Working Principle
1. **LDR sensors** detect the intensity of light from different directions.  
2. The **Arduino UNO** processes sensor values and determines the direction of maximum sunlight.  
3. **Servo motors** adjust the solar panel’s position along X and Y axes accordingly.  
4. The panel continuously tracks sunlight throughout the day, maximizing exposure.  

## 🖼️ Prototype Setup
The prototype was built using foam board as a lightweight frame for the solar panel, with LDR sensors mounted at four corners for light detection. Servo motors were fixed at pivot points for smooth panel movement.

## 📊 Results
- The solar tracker was able to orient itself towards the strongest light source in real time.  
- Achieved **higher energy capture efficiency** compared to a static panel in the same environment.  

## 🚀 Future Improvements
- Add real solar power measurement (with voltage/current sensors).  
- Incorporate battery storage and charging system.  
- Use machine learning to predict sunlight movement for even better efficiency.  

## 📂 Repository Structure
