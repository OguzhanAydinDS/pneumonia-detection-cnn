# 🫁 Pneumonia Detection via Chest X-Ray using Deep Learning

This deep learning project focuses on detecting pneumonia from chest X-ray images using convolutional neural networks (CNN). Both **DenseNet-121** and **ResNet50** architectures were tested to compare performance in medical image classification.

## 📌 Problem Statement

Pneumonia is a potentially life-threatening lung infection. Early detection through chest X-rays is crucial, and deep learning methods can support radiologists by automating the diagnostic process.

## 🧠 Model Overview

- Architectures:
  - **DenseNet-121**
  - **ResNet50**
- Framework: **TensorFlow / Keras**
- Transfer learning with fine-tuning
- Binary classification: Pneumonia vs. Normal

## 🖼️ Dataset

- Source: [Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- Total images: 5,800+
- Folder structure:
  ```
  chest_xray/
  ├── train/
  ├── val/
  └── test/
  ```

## ⚙️ Preprocessing

- Resizing to 224x224
- Image normalization
- Data augmentation: rotation, zoom, flip

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Curve

## 📈 Results

| Model       | Accuracy | F1 Score |
|-------------|----------|----------|
| ResNet50    | 90.8%    | 0.89     |
| DenseNet121 | **91.2%** | **0.90** |

DenseNet121 slightly outperformed ResNet50, achieving higher accuracy and better generalization on the test set.

## ▶️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/OguzhanAydinDS/pneumonia-detection-cnn.git
   ```
2. Open `pneumonia detection.ipynb` in Jupyter or Colab.
3. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) and place it in `chest_xray/` directory.

## 📘 Notes

This project showcases the use of **transfer learning** for medical image classification.  
Comparative analysis between DenseNet and ResNet was conducted using consistent training and evaluation pipelines.

## 📬 Contact

- [LinkedIn](https://www.linkedin.com/in/oguzhan-aydin-ds/)
- ✉️ oguzhanaydn@outlook.com
