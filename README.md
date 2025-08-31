# Smart Waste Segregation System ♻️

A smart AI-powered system for **automated waste segregation** using **image classification** and **sound analysis**.  
This project is designed to classify and sort waste into categories like **plastic, organic, glass, and metal cans**,  
helping improve waste management efficiency.  

---

## Features
- **Waste Classification** using a trained PyTorch model (`waste_classifier_final.pt`)
- **Audio-based Analysis** for additional classification support
- **Live Webcam Feed** integration with **PyQt6** user interface
- **Hardware Control** (Raspberry Pi 5 + rotating tray mechanism for sorting)
- Real-time waste detection and segregation results displayed in UI

---

## Tech Stack
- **Python 3.9+**
- **PyTorch** (ML model training & inference)
- **OpenCV** (image processing)
- **PyQt6** (desktop GUI)
- **SoundDevice / TensorFlow** (audio classification)
- **Raspberry Pi 5** (for hardware control)

---

## Project Structure

Smart-Waste-Segregation-System/
│── ADR.py # Audio-based waste recognition
│── ADT.py # Additional detection utilities
│── train_glass_model.py # Training script for glass classification
│── ui.py # PyQt6 GUI for live detection
│── waste_classifier_final.pt # Trained PyTorch model (weights)

## Conclusion
The **Smart Waste Segregation System** demonstrates how **AI and IoT can work together** to solve real-world problems in waste management.  
By combining **image recognition, audio analysis, and automated hardware control**, this project provides a scalable and efficient solution for cleaner, smarter, and more sustainable cities.  

---

*Developed by [DINESHkumar-D23](https://github.com/DINESHkumar-D23)
A Special Thanks to my teammates, Aswin S, Abdullah, and Aravind S, for implementing the project as a working prototype.
