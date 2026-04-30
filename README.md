# 🍽️ FoodDetect: Food Detection using YOLO

A deep learning-based food detection system built using YOLO architecture.  
This project focuses on detecting common food items and evaluating performance using standard object detection metrics.

---

## 📌 Overview

FoodDetect is designed to:
- Detect multiple food items in images
- Train using YOLO (Ultralytics)
- Evaluate using Precision, Recall, mAP, and F1-score
- Visualize training loss and performance metrics

---

## ⚙️ Model Details

- Model: YOLO (Ultralytics)
- Image Size: 640
- Training Epochs: 20
- Dataset Size:
  - Images: 3966
  - Instances: 5998

---

## 📊 Evaluation Metrics

| Metric      | Score |
|------------|------|
| Precision  | 0.843 |
| Recall     | 0.810 |
| mAP@50     | 0.864 |
| mAP@50-95  | 0.733 |
| F1-Score   | 0.826 |

---

## 📈 Training Loss Convergence

- Box Loss ↓ (improves localization)
- Classification Loss ↓ (improves class prediction)
- DFL Loss ↓ (improves bounding box quality)

Loss shows stable convergence from **Epoch 3 → 18**, indicating good training behavior.

---

## 📉 Graphs Included

### 1. Loss Curve
- Box Loss
- Classification Loss
- DFL Loss  
(Custom sunset-themed visualization)

### 2. Performance Metrics Graph
- Precision
- Recall
- mAP
- F1 Score  
(Advanced styled bar chart)

---

## 🚀 How to Run

### 1. Install Dependencies
```bash
pip install ultralytics matplotlib numpy
