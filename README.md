# CNN Image Classification (CIFAR-10)

## 📌 Project Overview
This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 categories.

Convolutional Neural Networks are state-of-the-art models for image classification tasks due to their ability to automatically learn spatial features from images.

---

## 🎯 Objectives
- Understand image classification using deep learning
- Build a CNN model using TensorFlow/Keras
- Train and evaluate the model on CIFAR-10 dataset
- Analyze model performance

---

## 📂 Dataset
- CIFAR-10 dataset (60,000 images)
- 10 classes (airplane, car, bird, cat, dog, etc.)
- Images size: 32x32 RGB

---

## 🧠 Model Architecture
The CNN model consists of:

- Conv2D (32 filters, 3x3 kernel) + ReLU
- MaxPooling2D
- Conv2D (64 filters, 3x3 kernel) + ReLU
- MaxPooling2D
- Flatten
- Dense (64 neurons, ReLU)
- Output layer (10 classes)

👉 CNN architectures are widely used in image classification and have evolved into models like AlexNet, VGG, and ResNet :contentReference[oaicite:1]{index=1}

---

## ⚙️ Training
- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- Epochs: 5

---

## 📊 Results
The model achieved:

Test Accuracy: 68%

👉 The model successfully learns basic image features but can be improved with deeper architectures or data augmentation.

---

## 📈 Visualization (Recommended Improvement)
(Add plots here if available)

- Accuracy vs Epoch
- Loss vs Epoch

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Run all cells:
   Runtime → Run all

---

## 🔗 Run on Google Colab
(https://colab.research.google.com/drive/1g5TwQw-CQxTL6GQfwh2uq7a2f3kxSBka?usp=sharing)

---

## 🔍 Limitations
- Simple CNN architecture
- Limited training epochs
- No data augmentation

---

## 🔧 Future Improvements
- Use deeper CNN (ResNet, VGG)
- Apply data augmentation
- Tune hyperparameters
- Add dropout to reduce overfitting

---

## 👤 Author
Guelleh


