# Diagnosing Acute Lymphoblastic Leukemia (ALL) Using CNN

A deep learning project that diagnoses Acute Lymphoblastic Leukemia (ALL) from blood sample images, comparing the performance of a Custom CNN against a Pretrained CNN (ResNet152V2).

---

## Overview

Acute Lymphoblastic Leukemia (ALL) is a type of blood cancer that affects white blood cells. Early and accurate diagnosis is critical for treatment. This project explores whether a lightweight custom CNN can match the performance of a heavy pretrained model like ResNet152V2 when classifying ALL from microscopic blood sample images.

---

## Dataset

- **Source:** [mehradaria/leukemia on Kaggle](https://www.kaggle.com/datasets/mehradaria/leukemia)
- **Type:** Microscopic blood sample images
- **Classes:** Early, Pro, Pre, Benign

## Models

### Custom CNN
- Built from scratch using convolutional, pooling, and dense layers
- Lightweight and trained specifically on this dataset

### Pretrained CNN — ResNet152V2
- Uses ResNet152V2 pretrained on ImageNet

## 🛠️ Requirements

Install dependencies with:
```bash
pip install -r requirements.txt
```

Key libraries:
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- KaggleHub
- Pandas, NumPy, Matplotlib, Seaborn

---

## How to Run

1. Clone the repo:
```bash
git clone https://github.com/ran-coder/Diagnosing-Leukemia-CNN.git
```
2. Install requirements:
```bash
pip install -r requirements.txt
```
3. Open and run the notebooks:
   - `custom_cnn(2).ipynb` — Custom CNN model
   - `pretrain_cnn(2).ipynb` — ResNet152V2 transfer learning model
