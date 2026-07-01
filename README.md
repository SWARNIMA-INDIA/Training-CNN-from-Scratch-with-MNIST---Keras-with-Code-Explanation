# Handwritten Digit Classification using CNN (MNIST)

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** from scratch using **TensorFlow/Keras** to classify handwritten digits (0–9) from the **MNIST dataset**. The model learns image features automatically through convolution and pooling layers, achieving **99.18% test accuracy**.

This project demonstrates the complete deep learning workflow, including data preprocessing, model building, training, evaluation, and prediction.

---

## 📂 Dataset

The project uses the **MNIST Handwritten Digits Dataset**, which contains:

- **70,000 grayscale images**
- **60,000 training images**
- **10,000 testing images**
- Image size: **28 × 28 pixels**
- 10 classes (Digits **0–9**)

---

## 🚀 Project Workflow

1. Load the MNIST dataset
2. Visualize sample handwritten digit images
3. Normalize pixel values (0–255 → 0–1)
4. One-hot encode labels
5. Reshape images for CNN input
6. Build the CNN architecture
7. Compile the model
8. Train the model
9. Save the best-performing model
10. Evaluate model performance on the test dataset

---

## 🏗 Model Architecture

The CNN architecture consists of:

- Conv2D (32 filters, 3×3, ReLU)
- MaxPooling2D
- Conv2D (64 filters, 3×3, ReLU)
- MaxPooling2D
- Flatten Layer
- Dense Layer (64 neurons, ReLU)
- Output Dense Layer (10 neurons, Softmax)

---

## 🛠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib

---

## 📊 Model Performance

| Metric | Value |
|---------|-------|
| Training Images | 60,000 |
| Testing Images | 10,000 |
| Epochs | 10 |
| Optimizer | RMSprop |
| Loss Function | Categorical Crossentropy |
| Test Accuracy | **99.18%** |

---

## 📁 Project Structure

```
├── CNN_MNIST.ipynb
├── model.weights.best.keras
├── README.md
```

---

## 📈 Results

The trained CNN successfully classifies handwritten digits with **99.18% test accuracy**, demonstrating the effectiveness of convolutional neural networks for image classification tasks.

---

## 🎯 Key Learning Outcomes

- Image preprocessing for deep learning
- CNN architecture design
- Feature extraction using convolution layers
- Downsampling with max pooling
- One-hot encoding
- Model training and validation
- Model evaluation using test accuracy
