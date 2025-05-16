# 🚗 Drowsy Driver Detection System using OpenCV and CNN 😴

A real-time drowsiness detection system that alerts drivers when signs of fatigue are detected using computer vision and deep learning. This project leverages **OpenCV** for video capture and **Convolutional Neural Networks (CNN)** for eye state classification.


## 🧠 Overview

Drowsy driving is a major cause of road accidents. This system monitors the driver’s eyes using a webcam and alerts them if their eyes remain closed for a certain period, indicating drowsiness.

- **Real-time detection** using webcam
- **Eye state classification**: Open vs Closed
- Alerts user via **sound alarm**
- Built using Python, OpenCV, and Keras/TensorFlow


## 🔍 Features

- 📷 Real-time face and eye detection using Haar cascades
- 🤖 CNN-based model to classify eye states
- 🔔 Alarm system to alert drowsy drivers
- 🛠 Modular and customizable code



## 🛠️ Tech Stack

- Python
- OpenCV
- Keras with TensorFlow backend
- NumPy
- Pygame (for alarm)
- Haar Cascades (for eye detection)




## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/drowsy-driver-detection.git
cd drowsy-driver-detection
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the Project
```bash
python main.py
```

## 🖼️ Demo

[🎥 Watch Demo](https://drive.google.com/file/d/15Cyad0Vypq_J39KhNBa6A5JouNkciN1G/view)


## Requirements
```bash
opencv-python
numpy
keras
tensorflow
pygame
```

##❗Notes
-Make sure your webcam is connected and accessible.
-Alarm will only sound after a defined number of consecutive frames with closed eyes.

## 📬 Contact
