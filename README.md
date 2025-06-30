# ☕ CoffeeSentinel-X

**CoffeeSentinel-X** is a mobile intelligence system built on the ODK-X platform to diagnose Coffee Wilt Disease (CWD) in real time using AI-driven image recognition. Designed for smallholder coffee farmers and extension workers, it provides instant feedback, GPS-linked records, and agronomic advice — even offline.

---

## 📌 Project Objectives

- Curate and annotate a verified image dataset of coffee plants (healthy and diseased).
- Train a lightweight convolutional neural network (CNN) model for on-device diagnosis.
- Integrate the model into an ODK-X workflow for real-time detection.
- Extend the platform with features relevant to coffee farming (plot mapping, record keeping, and advisory content).

---

## 🌿 Key Features

- **📷 On-device diagnosis:** Identify Coffee Wilt Disease through image capture.
- **🧠 AI-Powered:** Lightweight TensorFlow Lite model trained on curated field data.
- **📍 Geo-tagging:** GPS-based farm and plot tracking.
- **📶 Offline-first:** Fully functional in low-connectivity rural settings.
- **📋 ODK-X Integration:** Survey-based workflow with sync and task management.
- **📚 Farmer Tools:** Access to agronomic practices, soil condition notes, and pest control options.

---

## 🧠 Technical Stack

| Layer             | Technology                 |
|------------------|----------------------------|
| Data Collection  | ODK-X (Survey + Services)  |
| ML Inference     | TensorFlow Lite / PyTorch Mobile |
| Annotation Tool  | CVAT / Roboflow            |
| Backend (optional) | Django + PostgreSQL        |
| Deployment       | Android APK + Firebase / Local server |
| Repository       | GitHub                      |

---

## 📂 Repository Structure

