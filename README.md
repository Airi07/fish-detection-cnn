# Fish Detection & Classification System (CNN + Gradio)

An end-to-end Computer Vision application that detects and classifies fish species using a Convolutional Neural Network (CNN) and provides an interactive web UI built with Gradio.

---

## Key Features

- **CNN Classification Model:** Custom Convolutional Neural Network trained to accurately classify fish species categories.
- **Interactive Gradio Web UI:** User-friendly web interface allowing real-time image uploads and instant predictions with confidence metrics.
- **Data & Training Pipeline:** Complete image preprocessing, augmentation, training, and evaluation workflows built in Jupyter Notebooks.

---

## Model Weights (121MB)

Because the trained CNN model file (`fish_classifier_model.h5`) exceeds GitHub's 100MB per-file upload limit, it is hosted on Google Drive:

- 💾 **[Download Trained Model Weights (`fish_classifier_model.h5`)](https://drive.google.com/file/d/14wUjQ09KOuFBtQkCxYyDckVMbor8hvoS/view?usp=sharing)**

*Note: Please download `fish_classifier_model.h5` from the link above and place it directly inside the `Phyton Coding/` directory before launching the Gradio GUI.*

---

## Project Structure

```text
fish-detection-cnn/
│
├── Phyton Coding/             # Core scripts & notebooks
│   ├── training_dataset.ipynb # CNN architecture training & data preprocessing
│   └── gui_csc583.ipynb       # Gradio application interface & model inference
│
├── .gitignore                 # Excludes raw datasets and large binary model files
└── README.md                  # Project documentation
