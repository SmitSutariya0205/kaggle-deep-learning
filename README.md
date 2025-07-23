# Kaggle Deep Learning Challenges

This repository contains solutions to deep learning problems from Kaggle competitions and datasets. Each notebook aims to demonstrate practical applications of deep learning techniques using TensorFlow and Keras.

---

## First Commit: MNIST Digit Classification

### Notebook
`mnist_digit_classification_tensorflow.ipynb`

### Problem Description
The MNIST dataset consists of grayscale images of handwritten digits (0 to 9). The objective is to classify each image into one of the ten digit classes using a neural network.

### Key Details
- **Input:** 28x28 grayscale images, flattened to 784 features
- **Model:** Feedforward neural network (Dense layers with ReLU and Softmax)
- **Labels:** Integer encoded (not one-hot encoded)
- **Loss Function:** `SparseCategoricalCrossentropy`
- **Optimizer:** `Adam`
- **Output:** Probabilities over 10 classes
- **Evaluation:** Accuracy and confusion matrix using predictions obtained via `argmax()`

### Preprocessing
- Normalized input pixel values from `[0, 255]` to `[0.0, 1.0]`
- Extracted labels from the dataset
- Separated features (X) and labels (y)

---

