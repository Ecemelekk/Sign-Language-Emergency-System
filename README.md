# Sign Language Emergency Response System (SLERS)

## 📌 Project Overview
This project is an AI-powered assistive technology designed to enable individuals with hearing and speech impairments to request immediate assistance independently during emergencies. The system bridges the gap between human gesture recognition and physical emergency alert mechanisms using AI and IoT integration.

## 🛠 Technical Stack
* **AI/ML:** PictoBlox (Machine Learning Environment), Computer Vision
* **Hardware:** Arduino Uno, LED-based Warning Mechanism
* **Communication:** Serial Communication (between PC and Arduino)
* **Methodology:** Custom dataset creation, model training, and real-time inference.

## 🚀 Key Features
* **Emergency Recognition:** Real-time detection of three critical emergency signals: Fire, Accident, and Security Threat.
* **High Accuracy:** The model achieved approximately 98% accuracy during testing phases.
* **Hardware-Software Integration:** The AI model processes visual input in real-time and triggers physical alerts via an Arduino-controlled LED system.
* **Accessibility:** Designed with low-cost components and modular architecture.

## 👨‍🏫 Pedagogical & Engineering Impact
Developed as part of my work with the "Zirve Takımı," this project demonstrates the practical application of TinyML and computer vision in disaster management and assistive technology. It serves as a robust proof-of-concept for integrating AI decision-making with physical hardware.

---

### How to use this repository
1.  **Dataset:** Located in the /dataset folder.
2.  **Model:** The exported model is available in the /model directory.
3.  **Arduino Code:** The .ino file for the hardware alert system can be found in the /arduino_code folder.
