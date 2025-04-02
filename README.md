# CNN CIFAR-10 Image Classification 🧠🖼️

A deep learning project for image classification using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset, implemented in PyTorch. This project includes data augmentation, performance evaluation, and training visualization.

---

## 🗂️ Project Overview

- **Dataset**: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- **Framework**: PyTorch + TorchMetrics
- **Goal**: Classify images into 10 categories (e.g., airplane, car, dog, etc.)
- **Techniques Used**:
  - Data Augmentation (e.g., Horizontal Flip, Random Crop)
  - CNN with multiple Conv + Pool layers
  - Accuracy tracking via TorchMetrics
  - Visualization of training vs validation performance

---

## 🧪 Model Architecture

- 2 Convolutional blocks with ReLU and MaxPooling
- Fully connected layers (512 → 256 → 10)
- Lazy layers used for input shape flexibility

---

## 📊 Results

- Visualized training/validation loss and accuracy
- Final accuracy: 0.85
- Uses GPU if available for acceleration

