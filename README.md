# 🧠 MNIST10 Image Classifier using Convolutional Neural Network (CNN)

This project implements a CNN-based image classifier trained on the MNIST10 dataset, which consists of handwritten digits from 0 to 9. The model learns to classify grayscale images into one of the ten digit classes with high accuracy.

---

## 📚 Dataset

- **Name**: MNIST (10 classes — digits 0 through 9)
- **Source**: [Yann LeCun's MNIST Database](http://yann.lecun.com/exdb/mnist/)
- **Shape**: 28x28 grayscale images
- **Total Images**: 70,000 (60,000 training + 10,000 test)

---

## 🧠 Model Architecture

A simple yet effective CNN was used with the following structure:

- **Input Layer**: 28x28 grayscale image
- **Conv2D Layer 1**: 32 filters, 3x3 kernel, ReLU
- **Conv2D Layer 2**: 64 filters, 3x3 kernel, ReLU
- **MaxPooling2D Layer 1**: 2x2 pool size
- **MaxPooling2D Layer 2**: 2x2 pool size
- **Flatten Layer**
- **Dense Layer**: 128 units, ReLU
- **Output Layer**: 10 units (Softmax)

---

## 📈 Model Performance

| Metric        | Value     |
|---------------|-----------|
| Training Acc. | ~99%      |
| Test Acc.     | ~98%      |
| Loss Function | Categorical Crossentropy |
| Optimizer     | Adam      |

---

## 🚀 How to Run the Code

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/mnist10-cnn-classifier.git
   cd mnist10-cnn-classifier
