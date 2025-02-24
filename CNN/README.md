# 📊 MNIST Handwritten Digit Classification with ANN and CNN

This project demonstrates how to build and evaluate Artificial Neural Network (ANN) and Convolutional Neural Network (CNN) models using the **Keras MNIST dataset**. The goal is to classify handwritten digits (0–9) with high accuracy.

---

## 🔍 **Project Overview**

- **Dataset**: [MNIST Handwritten Digits](http://yann.lecun.com/exdb/mnist/)  
  The dataset contains **60,000 training images** and **10,000 testing images** of handwritten digits (each image is 28x28 pixels in grayscale).

- **Models Implemented**:
  - **ANN (Artificial Neural Network)**: A basic feedforward neural network.
  - **CNN (Convolutional Neural Network)**: A deep learning model designed to capture spatial hierarchies in images.

---

## 🚀 **Results**

| Model | Accuracy | Loss  | Epochs |
|-------|----------|-------|--------|
| ANN   | 0.9050   | 0.3920| 2      |
| CNN   | 0.9775   | 0.0990| 5      |

- The **CNN** significantly outperformed the **ANN** due to its ability to capture spatial relationships in images using convolution and pooling layers.

---

## 📦 **Requirements**

Make sure you have the following libraries installed:

```bash
pip install tensorflow keras numpy matplotlib
```

---


## 📊 **Key Observations**

- The **ANN** performed reasonably well, achieving ~90% accuracy in just 2 epochs.
- The **CNN** reached a much higher accuracy of ~97.75%, showcasing its strength in image classification tasks.
- Increasing the number of epochs or adding more convolutional layers could potentially improve the performance further.

---

## 📜 **License**

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 **Acknowledgements**

- [Keras Documentation](https://keras.io/)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

