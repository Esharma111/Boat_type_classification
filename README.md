
---

## 🧠 Problem Statement

> Marina Pier Inc. wants to eliminate human error in identifying boat types at San Francisco port. An automated, bias-free image classification model is needed, capable of running efficiently on mobile devices.

---

## 🏗️ Models Implemented

### 1. CNN from Scratch
- Built using Keras Sequential API
- Trained for 20 epochs
- Achieved moderate accuracy (~42%)

### 2. MobileNetV2 (Transfer Learning)
- Pre-trained on ImageNet
- Only top layers are trainable
- Trained for 50 epochs with EarlyStopping
- Lightweight and optimized for mobile
- Achieved higher accuracy (~86.84%)

---

## 📊 Evaluation Metrics

- **Loss**
- **Accuracy**
- **Precision**
- **Recall**
- **Confusion Matrix**
- **Classification Report**
- **Top-3 Prediction Visualizations**

---

## 🔍 Observations

- MobileNetV2 outperformed custom CNN in both speed and accuracy
- Better generalization and confidence in predictions

