<div align="center">

# 🐟 Fish Species Identification System
### *End-to-End Deep Learning Classification & Interactive Web UI*

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)](https://python.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow&logoColor=white)](https://tensorflow.org)
[![Gradio](https://img.shields.io/badge/Gradio-UI%20Framework-orange?logo=gradio&logoColor=white)](https://gradio.app)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Airi07/fish-detection-cnn/blob/main/Phyton%20Coding/gui_csc583.ipynb)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

### ⚡ [Click Here to Run Live Demo in Colab](https://colab.research.google.com/github/Airi07/fish-detection-cnn/blob/main/Phyton%20Coding/gui_csc583.ipynb)

</div>

---

## 📌 Project Overview

This repository features a **Computer Vision pipeline** engineered to classify fish species from image inputs. Built using a custom **Convolutional Neural Network (CNN)** architecture and deployed via an interactive **Gradio web interface**, the system enables real-time inference with probability distributions.

> **Key Focus:** Automating marine biology species classification to support biodiversity tracking and fishing yield quality assurance.

---

## 🛠️ Architecture & Tech Stack

| Domain | Technology | Purpose |
| :--- | :--- | :--- |
| **Deep Learning** | `TensorFlow` / `Keras` | Custom CNN architecture for multi-class image classification |
| **Data Processing** | `NumPy`, `Pillow` | Image normalization, batching, and array manipulation |
| **UI & Inference** | `Gradio` | Interactive web GUI with file drag-and-drop & webcam capture |
| **Deployment** | `Google Colab` + `gdown` | GPU runtime execution with automated cloud model ingestion |

---

## 🌟 Key Features

* **Real-Time Classification:** Instant multi-class probability scoring across fish species.
* **Flexible Input Methods:** Supports local file uploads and live webcam capture.
* **Automated Cloud Weight Recovery:** Integrated `gdown` script fetches 121MB model weights dynamically from cloud storage on launch.
* **Top-3 Confidence Metric:** Displays primary species predictions along with alternative probability candidates.

---

## 🚀 Quick Start Guide

### Option 1: One-Click Colab Execution (Recommended)

1. Click the **[Open in Colab](https://colab.research.google.com/github/Airi07/fish-detection-cnn/blob/main/Phyton%20Coding/gui_csc583.ipynb)** badge above.
2. Ensure GPU runtime is active: `Runtime` ➔ `Change runtime type` ➔ `T4 GPU`.
3. Execute all cells (`Ctrl + F9`). The notebook automatically fetches model weights and launches a public `gradio.live` link.

### Option 2: Local Installation

```bash
# 1. Clone the repository
git clone [https://github.com/Airi07/fish-detection-cnn.git](https://github.com/Airi07/fish-detection-cnn.git)
cd fish-detection-cnn

# 2. Install required packages
pip install tensorflow gradio pillow numpy gdown

# 3. Launch notebook or app script
jupyter notebook "Phyton Coding/gui_csc583.ipynb"
