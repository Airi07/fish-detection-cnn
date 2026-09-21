# Fish Detection & Classification System (CNN + Gradio)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Airi07/fish-detection-cnn/blob/main/Phyton%20Coding/gui_csc583.ipynb)

An end-to-end Computer Vision application that detects and classifies fish species using a Convolutional Neural Network (CNN) and provides an interactive web UI built with Gradio.

---

## 🚀 Interactive Live Demo

You can test and run this project immediately in your browser via Google Colab:

1. Click the **[Open in Colab](https://colab.research.google.com/github/Airi07/fish-detection-cnn/blob/main/Phyton%20Coding/gui_csc583.ipynb)** badge above.
2. Select **Runtime** > **Change runtime type** > Set hardware accelerator to **T4 GPU**.
3. Run all cells (`Ctrl + F9`). The notebook automatically downloads the trained model weights from Google Drive and generates a live public Gradio web link!

---

## Key Features

- **CNN Classification Model:** Custom Convolutional Neural Network trained to accurately classify fish species categories.
- **Interactive Gradio Web UI:** Drag-and-drop web interface allowing real-time image uploads and instant predictions with confidence scores.
- **Automated Weight Ingestion:** Built-in script that automatically fetches trained model weights from cloud storage upon execution.

---

## Project Structure

```text
fish-detection-cnn/
│
├── Phyton Coding/             # Core scripts & notebooks
│   ├── training_dataset.ipynb # CNN architecture training & data preprocessing
│   └── gui_csc583.ipynb       # Gradio application interface & model inference
│
├── .gitignore                 # Excludes raw datasets and heavy binary files
└── README.md                  # Project documentation
