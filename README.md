# ☕ CoffeeSentinel-X

**CoffeeSentinel-X** is an AI-powered mobile system built on **ODK-X** for diagnosing **Coffee Wilt Disease (CWD)** in real time and supporting smallholder coffee farmers with decision tools and agronomic advice.

---

## 📚 Table of Contents

- [🔍 Project Objectives](#-project-objectives)
- [🌿 Key Features](#-key-features)
- [🧠 Technical Stack](#-technical-stack)
- [📂 Repository Structure](#-repository-structure)
- [🚀 Getting Started](#-getting-started)
- [🏗️ Model Overview](#️-model-overview)
- [🌍 Use Cases](#-use-cases)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [📅 Project Status](#-project-status)
- [🌟 Acknowledgements](#-acknowledgements)
- [📬 Contact](#-contact)

---

## 🔍 Project Objectives

- ✅ Curate and annotate a dataset of coffee plants (healthy and diseased)
- ✅ Train a CNN-based image model for CWD detection
- ✅ Integrate model with ODK-X for mobile usage
- ✅ Extend with features useful to coffee farmers (mapping, advice, tracking)

---

## 🌿 Key Features

- 📷 **Camera-based Diagnosis**: Detects Coffee Wilt Disease from plant images.
- 🧠 **On-device ML Model**: Efficient TensorFlow Lite implementation.
- 📍 **GPS Logging**: Location-aware plot and plant tracking.
- 🔁 **Offline-first Workflow**: Designed for rural areas with low connectivity.
- 📋 **ODK-X Forms**: Survey-based task and data collection.
- 🌱 **Farmer Support Tools**: Guidance, logging, and market tips (in development).

---

## 🧠 Technical Stack

| Component         | Technology                |
|------------------|---------------------------|
| Survey Interface | ODK-X (Survey, Services)  |
| ML Inference     | TensorFlow Lite           |
| Annotation       | CVAT or Roboflow          |
| Backend (optional) | Django + PostgreSQL     |
| Deployment       | Android APK, Firebase     |
| Hosting          | GitHub                    |

---

<details>
<summary>📂 <strong>Repository Structure</strong></summary>

