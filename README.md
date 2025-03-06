# Potato-Disease-Classifier-TM

**Repository Structure**

potato-disease-classifier-tm/
│── models/
│   ├── keras_model.h5
│   ├── saved_model/
│── dataset/
│   ├── healthy/
│   ├── early_blight/
│   ├── late_blight/
│── notebooks/
│   ├── test_model.ipynb
│── README.md
│── requirements.txt
│── app.py  (Optional Flask or Streamlit app for inference)

# Potato Disease Classifier - Teachable Machine

This repository contains a deep learning model trained using **Teachable Machine by Google** to classify potato leaves into three categories:
- Healthy 🍃
- Early Blight 🍂
- Late Blight 🍄

## 📌 Features:
- Model trained on image classification dataset using **Teachable Machine**.
- Exported as a **Keras model** (`.h5`) and **TensorFlow SavedModel** format.
- Simple **Flask/Streamlit app** for inference.
- **Jupyter Notebook** for testing the model.

## 📁 Folder Structure:
- `models/` - Contains exported Teachable Machine models (Keras `.h5` and SavedModel format).
- `dataset/` - Sample images for testing.
- `requirements.txt` - Python dependencies.

## 🔧 Setup & Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/nithyashreesenguttuvan/Potato-Disease-Classifier-TM.git
   cd potato-disease-classifier-tm
