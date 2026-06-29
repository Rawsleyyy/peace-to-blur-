# ✌️ Peace to Blur: Real-Time Hand Gesture Camera Blur

![Python](https://img.shields.io/badge/Python-3.12+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-orange.svg)
![MediaPipe](https://img.shields.io/badge/MediaPipe-AI%20Tracking-green.svg)

A sleek, real-time camera blurring application built with Python. The application leverages computer vision to dynamically apply a smooth Gaussian blur filter to the live video feed instantly upon detecting a **Peace / V Sign** hand gesture. Perfect for quick privacy control during video streams!

---

## 🚀 Features

* **High-Fidelity Hand Tracking:** Powered by Google MediaPipe Hands for blazing-fast, low-latency landmark detection.
* **Instant Auto-Blur:** Smoothly overlays a full-frame Gaussian Blur filter the exact moment the gesture is validated.
* **Optimized & Modular:** Clean Python architecture with dedicated helper functions for easy scalability.
* **Seamless Controls:** Lightweight implementation with quick keyboard interruption.

## 🛠️ Tech Stack

* **Language:** Python 3.12+
* **Frameworks & Libraries:** OpenCV (v4.x), Google MediaPipe

## 📦 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Rawsleyyy/peace-to-blur.git](https://github.com/Rawsleyyy/peace-to-blur.git)
   cd peace-to-blur

2. **Install the required dependencies:**
   ```bash
   pip install opencv-python mediapipe
   
## 💻 How to Run
Launch the application directly from your terminal:
  '''bash
  python foto.py

> 💡 Pro-Tip: Press the Esc key at any time while the camera window is focused to safely exit the application.
