# Handwritten Digit Recognition (CNN)

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) using the MNIST dataset.

---

## 📊 Project Highlights
- Built a CNN model for image classification
- Applied normalization and preprocessing for better training
- Used dropout to reduce overfitting
- Visualized model performance and predictions
- Achieved **99.04% test accuracy**

---

## 🗂 Dataset
- MNIST Handwritten Digits dataset  
- 60,000 training images and 10,000 testing images  
- Grayscale images of size 28×28 pixels  

Dataset loaded using TensorFlow:
```python
from tensorflow.keras.datasets import mnist
(X_train, y_train), (X_test, y_test) = mnist.load_data()
```

---

## 🧠 Model Architecture
- Conv2D → ReLU → MaxPooling  
- Conv2D → ReLU → MaxPooling  
- Flatten  
- Dense (128)  
- Dropout (0.5)  
- Dense (10, Softmax)  

---

## 🛠 Technologies Used
- Python
- TensorFlow / Keras
- NumPy, Matplotlib

---

## 📈 Results
- Test Accuracy: 99.04%
- Sample Predictions

---


## 💡 Key Learning

Learned how CNNs extract spatial features from images and how regularization techniques like dropout improve model generalization.

Project completed as part of CodeAlpha Machine Learning Internship
