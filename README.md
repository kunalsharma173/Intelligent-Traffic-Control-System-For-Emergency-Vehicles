# Intelligent Traffic Control System for Emergency Vehicles

## Overview
Traffic congestion poses a major challenge, especially for emergency vehicles that require clear passage. This project introduces an **Intelligent Traffic Control System** leveraging **Machine Learning (ML) and IoT** to dynamically adjust traffic signals for emergency vehicles. The system employs **audio recognition and image processing** to detect emergency vehicles and clear traffic automatically.

## Key Features
- **Real-time Emergency Vehicle Detection:** Utilizes **ML models** for siren sound and image recognition.
- **Automated Traffic Signal Control:** Dynamically switches traffic lights to green for emergency vehicles.
- **Embedded System Implementation:** Runs on a **Raspberry Pi** with integrated sensors.
- **Machine Learning Integration:** Trained on diverse datasets to ensure high accuracy in varying conditions.
- **Scalable & Efficient:** Eliminates RFID dependency and improves real-time responsiveness.

## System Architecture
The system consists of the following components:
1. **Raspberry Pi Controller:** Orchestrates operations, executes ML predictions.
2. **Microphone & Camera:** Captures siren sounds and vehicle images.
3. **ML Model:** Processes audio spectrograms and images to classify emergency vehicles.
4. **Signal Interface:** Controls traffic lights based on ML predictions.

## Installation & Setup
### 1. Install Dependencies
Ensure **Python** is installed, then run:
```bash
pip install -r requirements.txt
```

### 2. Deploy ML Model
- Load the trained **TensorFlow Lite model** onto the Raspberry Pi.
- Store the **spectrogram-based dataset** for real-time prediction.

### 3. Run the System
Execute the main script to start processing traffic signals:
```bash
python main.py
```

## Usage
1. **System Activation:** Continuously monitors traffic signals.
2. **Emergency Detection:** Recognizes sirens and emergency vehicle images.
3. **Traffic Clearance:** Automatically changes traffic signals for emergency vehicles.

## Technology Stack
- **Programming Language:** Python
- **Machine Learning Framework:** TensorFlow, OpenCV
- **Hardware:** Raspberry Pi, Microphone, Camera
- **Embedded System:** IoT-based traffic management

## Results & Performance
- Achieved **87% accuracy** in classifying emergency vehicle sirens.
- Successfully reduced emergency response time by dynamically controlling traffic signals.
- Scalable to multiple intersections with **minimal hardware modifications**.

## Future Enhancements
- **Extended Training Data:** Improve ML model accuracy for varied siren types.
- **Cloud Integration:** Enable remote monitoring and real-time updates.
- **V2X Communication:** Enhance vehicle-to-infrastructure interactions for smarter traffic management.

## Conclusion
This system **intelligently manages traffic signals** for emergency vehicles, enhancing response times and reducing congestion. By leveraging **ML and IoT**, it offers a scalable and efficient solution for modern smart cities.

---
Developed by **Kunal Sharma & Saswath** | Dayananda Sagar University

