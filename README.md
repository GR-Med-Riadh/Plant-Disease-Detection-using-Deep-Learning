# Plant Disease Detection using Deep Learning (MobileNetV2)

This repository contains a comprehensive Jupyter Notebook demonstrating the application of **Transfer Learning** to detect plant diseases from leaf images. The project covers the full pipeline from data preprocessing to real-time inference.

## 🌟 Project Overview
Early detection of plant diseases is vital for global food security. This project uses a deep learning approach to automate the diagnostic process, classifying images into 15 distinct categories of healthy and diseased plant leaves.

## 🛠️ Technical Highlights
- **Model Architecture:** MobileNetV2 (optimized for speed and efficiency).
- **Technique:** Transfer Learning (Feature Extraction + Fine-tuning).
- **Optimization:** Categorical Crossentropy loss with the Adam optimizer.
- **Regularization:** Dropout layer (0.2) to ensure the model generalizes well to unseen data.
- **Tools:** TensorFlow, Keras, OpenCV, and Matplotlib.

## 📊 Key Results
- **Dataset:** 20,638 total images (15 classes).
- **Validation Accuracy:** Achieved **~90% accuracy** within just 10 training epochs.
- **Real-Time Ready:** The repository includes code for live prediction using a webcam feed.

## 📂 Contents
- `Workshop Deep Learning (1).ipynb`: The complete project workflow, including:
  - Data loading and augmentation.
  - Model building and summary.
  - Training and validation performance logs.
  - Real-time inference script using OpenCV.
## The link of the dataset
  https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset
## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/plant-disease-detection.git](https://github.com/your-username/plant-disease-detection.git)
