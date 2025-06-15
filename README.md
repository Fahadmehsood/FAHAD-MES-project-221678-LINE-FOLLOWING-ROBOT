# Line Following Robot 🤖

[![Arduino](https://img.shields.io/badge/Arduino-00979D?logo=Arduino&logoColor=white)](https://www.arduino.cc/)
[![ESP32](https://img.shields.io/badge/ESP32-E7352C?logo=espressif&logoColor=white)](https://www.espressif.com/)

An autonomous line following robot with data logging and wireless communication capabilities.

## 🎯 Overview

This robot autonomously follows a black line on white surface using IR sensors, with obstacle detection and comprehensive data logging features. Built for the Micro Controllers Lab course at Air University, Islamabad.

## ✨ Features

- **Autonomous Navigation**: 5 IR sensors for precise line following
- **Obstacle Detection**: Ultrasonic sensor with servo scanning
- **Data Logging**: SD card storage of operational data
- **Wireless Communication**: ESP32 integration
- **Real-time Display**: 16x4 LCD status monitor
- **Power Monitoring**: Current and voltage sensors

## 🔧 Key Components

- Arduino Mega 2560 (Main Controller)
- ESP32 (Wireless Communication)
- 5x TCRT5000 IR Sensors
- HC-SR04 Ultrasonic Sensor
- L298N Motor Driver
- 16x4 LCD Display
- SD Card Module
- Custom PCB

## 📥 Quick Start

1. **Hardware Setup**: Assemble chassis and connect components per circuit diagram
2. **Software**: Upload code to Arduino Mega and ESP32
3. **Calibration**: Calibrate IR sensors for black/white detection
4. **Run**: Place on track and press start button

## 💻 Code Structure

```
├── line_follower_main.ino      # Main Arduino code
├── esp32_communication.ino     # ESP32 wireless code
└── sensor_functions.cpp        # Utility functions
```

## 🧪 Performance

- **Accuracy**: >95% line following precision
- **Detection Range**: 2-400cm obstacle detection
- **Battery Life**: 2-3 hours continuous operation
- **Total Cost**: PKR 8,000-9,000

## 👥 Team

- **Fahad Mahmood** (221678) - PCB Design & Documentation
- **Hammad Mustafa** (221711) - Software & Integration
- **Supervisor**: Engr. Umer Farooq

## 🎓 Institution

Air University, Islamabad  
Department of Mechatronics Engineering  
Course: MT359-L Micro Controllers Lab

## 📄 License

MIT License - Feel free to use and modify!
