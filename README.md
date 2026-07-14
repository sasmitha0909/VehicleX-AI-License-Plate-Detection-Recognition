# VehicleX-AI: Advanced Vehicle License Plate Detection & Recognition

## 📌 Overview

VehicleX-AI is an AI-powered Automatic License Plate Recognition (ALPR) system that detects vehicle license plates and recognizes the characters from them. The project combines object detection and optical character recognition (OCR) techniques to automate license plate identification from vehicle images.

---

## 🚀 Features

* Detects vehicle license plates from images.
* Recognizes license plate text using deep learning.
* Image preprocessing for improved recognition accuracy.
* End-to-end automated license plate recognition pipeline.
* Easy to extend for real-time video processing.

---

## 🛠️ Tech Stack

* Python
* OpenCV
* YOLO (License Plate Detection)
* CRNN (Character Recognition)
* TensorFlow / Keras
* Google Colab

---

## 📂 Project Structure

```text
VehicleX-AI/
│── preprocessing.py
│── detection.py
│── crnn_model.py
│── train_crnn.py
│── pipeline.py
│── models/
│── dataset/
│── outputs/
│── README.md
```

---

## ⚙️ Workflow

1. Load the input vehicle image.
2. Detect the license plate using YOLO.
3. Crop and preprocess the detected license plate.
4. Recognize characters using the CRNN model.
5. Display the extracted license plate number.

---

## 📊 Results

The model successfully detects vehicle license plates and extracts license numbers from input images. The modular pipeline enables accurate detection and recognition while allowing future enhancements for real-time applications.

---

## 💡 Future Improvements

* Real-time video stream support.
* Multi-vehicle detection.
* Improved OCR accuracy under low-light conditions.
* Vehicle tracking and database integration.
* Automatic authorized/unauthorized vehicle verification.

---

## 🎯 Applications

* Smart Parking Systems
* Traffic Monitoring
* Toll Booth Automation
* Access Control Systems
* Campus and Office Security
* Law Enforcement

---

## 👩‍💻 Author

**Savitha U**

If you found this project helpful, consider giving it a ⭐ on GitHub.
