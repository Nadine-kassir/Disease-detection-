# 🩺 Pneumonia Detection from Chest X-rays

**Deep learning model that classifies chest X-ray images as Normal or Pneumonia with 97% recall and 88% accuracy.**

---

## 🎯 Overview
This project detects pneumonia from chest X-rays using deep learning to assist radiologists in **fast preliminary screening** and **prioritizing urgent cases**.

---

## 📊 Results
- **Recall:** 97% (caught 380 out of 390 pneumonia cases)  
- **Accuracy:** 88%  
- **Precision:** 86%  
- **Dataset:** 5,863 chest X-ray images from Kaggle  

---

## 🛠️ Tech Stack
- **TensorFlow / Keras**  
- **Transfer Learning (MobileNetV2)**  
- **Python, NumPy, Matplotlib**

---

## 🔑 Approach
I implemented and compared two approaches:

1. **Custom CNN** – Built from scratch  
2. **Transfer Learning with MobileNetV2** – Pre-trained model with fine-tuning  

Transfer learning proved **more effective** in terms of accuracy and feature extraction.

---

## 💡 Key Technical Decisions
To ensure robust model performance and prevent overfitting:

- Added `validation_split=0.1` for proper model evaluation  
- Set `shuffle=True` for training data to improve

