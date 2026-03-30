# PneumoVision
AI-based chest X-ray pneumonia detection using CNN (DenseNet121)

## 📌 Overview
PneumoVision is an AI-based healthcare project that detects pneumonia from chest X-ray images using deep learning. The model is built using Convolutional Neural Networks (CNN) with DenseNet121 architecture to assist in early and accurate diagnosis.

---

## 🚀 Features
- 🩺 Detects pneumonia from chest X-ray images  
- 🤖 Uses DenseNet121 deep learning architecture  
- 📊 Achieves approximately 80–85% accuracy  
- ⚡ Fast and automated prediction system  

---

## Technologies Used
- Python  
- TensorFlow / Keras  
- OpenCV  
- Jupyter Notebook  

---

## ⚙️ How It Works
1. 📥 Load chest X-ray dataset (train, validation, test)  
2. 🔄 Preprocess images (resizing, normalization, augmentation)  
3. 🧠 Train CNN model using DenseNet121  
4. 📊 Evaluate model performance  
5. 🔍 Predict whether the X-ray is **Normal** or **Pneumonia**  

---

## 📊 Results

### 📈 Training & Validation Accuracy
![Accuracy](screenshots/accuracy.png)

### 🔍 Prediction Output
![Prediction](screenshots/prediction.png)

---

## 💾 Model Saving
The trained model is saved in `.h5` format so that it can be easily loaded into an API for deployment:

```python
model.save("pneumovision_model.h5")
