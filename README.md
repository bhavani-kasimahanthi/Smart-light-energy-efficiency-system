Smart Light Energy Efficiency System

Project Overview  
This project implements an energy-efficient smart lighting system that automatically controls lights based on vehicle detection and ambient light conditions.

The system ensures that the light turns ON only when a vehicle passes, and remains OFF otherwise, helping to significantly reduce unnecessary power consumption.

Key Features  
- Light turns ON only when a vehicle is detected  
- Automatic control using IR sensor for vehicle detection  
- Uses LDR sensor to sense ambient light  
- Reduces energy wastage during low traffic conditions  
- Suitable for smart street lighting applications  

Hardware Components  
- Microcontroller (Arduino / ESP32)  
- IR Sensor (for vehicle detection)  
- LDR Sensor (for ambient light detection)  
- LEDs / Street light module  
- Resistors, jumper wires  
- Power supply  

How It Works  
1. The LDR sensor checks whether it is day or night.  
2. If it is dark, the system becomes active.  
3. When a vehicle passes, the IR sensor detects motion.  
4. The microcontroller turns the light ON.  
5. After the vehicle passes, the light turns OFF automatically.  
6. This process repeats only when vehicles are detected.  

Outcome  
This system provides an intelligent and energy-efficient solution for lighting by ensuring that lights are activated only when required, making it ideal for smart roads and street-light automation.
