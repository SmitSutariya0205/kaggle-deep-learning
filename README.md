# Kaggle Deep Learning Challenges

This repository contains solutions to deep learning problems using TensorFlow and Keras.

---

## 1. MNIST Digit Classification  
**Notebook:** `mnist_digit_classification_tensorflow.ipynb`

A simple neural network trained on the MNIST handwritten digits dataset.

**Highlights**
- Input: 28×28 grayscale images  
- Architecture: Dense layers (ReLU + Softmax)  
- Loss: `SparseCategoricalCrossentropy`  
- Optimizer: `Adam`  
- Evaluation: Accuracy + confusion matrix  

---

## 2. Cat vs Dog Image Classification (CNN)  
**Notebook:** `cat_dog_cnn_classification.ipynb`

A Convolutional Neural Network trained on a dataset of 2000 images (1000 cats, 1000 dogs).

**Highlights**
- Input: Resized RGB images (e.g., 150×150×3)  
- Architecture:
Conv2D → MaxPool
Conv2D → MaxPool
Conv2D → MaxPool
Flatten → Dense(128) → Dropout(0.5)
Dense(2, Softmax)

yaml
Copy code
- Labels: One-hot encoded  
- Loss: `CategoricalCrossentropy`  
- Optimizer: `Adam`  
- Preprocessing: Normalization, train-test split  
- Data Augmentation: rotation, zoom, horizontal flip  

---

## Repository Structure
├── mnist_digit_classification_tensorflow.ipynb
├── cat_dog_cnn_classification.ipynb
├── README.md
