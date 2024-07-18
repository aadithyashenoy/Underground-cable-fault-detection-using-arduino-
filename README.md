# Cable Fault Detection

This project focuses on detecting cable faults in power transmission and distribution systems. The detection system utilizes the concept of Ohm's law to determine the distance from the base station to the cable fault location. This project is developed as part of the Bachelor of Engineering degree requirements in Electronics and Communication Engineering.

## Abstract
Cable fault detection is crucial for maintaining the reliability of electrical networks by minimizing downtime and reducing repair costs. This project aims to detect the exact location of faults in cables using a simple implementation based on Ohm’s law. When a fault occurs, the distance to the fault is displayed on a liquid crystal display (LCD).

## Introduction
Cable faults pose significant challenges in power transmission and distribution systems. Detecting cable faults promptly is essential for maintaining system integrity and minimizing power outages. This project uses advanced fault detection techniques to improve accuracy, reduce downtime, and enhance system reliability.

## Methodology
### Components Used
- Arduino Microcontroller
- Series resistors
- DC power supply
- Liquid Crystal Display (LCD)
- Analog to Digital Converter (ADC)
- Fault switches

### Block Diagram
[Include a block diagram image here]

### Circuit Diagram
[Include a circuit diagram image here]

### Working
The system applies DC voltage across a series of resistors representing the cable. The current varies depending on the fault location, and this change is fed to the Arduino via an ADC. The Arduino calculates the fault distance and displays it on the LCD.

## Results
The system accurately detects faults and displays the distance to the fault on the LCD for all three phases.

## Future Scope
The project can be further enhanced by integrating IoT for remote monitoring and real-time data analysis to improve fault detection and system reliability.

## Conclusion
The proposed cable fault detection system offers a cost-effective and accessible solution for detecting and monitoring faults in cables, making it valuable for both professionals and educational purposes.
