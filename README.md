# Anomaly Detection Convolutional Neural Network Architecture

## 📌 Project Overview

This project explores the use of Convolutional Neural Networks (CNNs) for anomaly detection in image data. It focuses on building a custom CNN architecture to classify and detect anomalies in a dataset of images, leveraging techniques like data preprocessing, training-validation splitting, and model evaluation using accuracy and visualizations.

---

## 🔍 Key Components

### 1. Data Preprocessing and Exploration
- Data is loaded, resized, and normalized.
- Exploratory visualizations are used to understand the distribution and structure of the dataset.

### 2. Model Architecture
- A custom CNN is designed from scratch using layers like `Conv2D`, `MaxPooling2D`, `Dropout`, and `Dense`.
- The model is compiled with appropriate loss and optimizer functions.

### 3. Training and Evaluation
- The model is trained with training and validation datasets.
- Evaluation metrics such as accuracy, loss, and visual plots (e.g., confusion matrix) are used to assess performance.

### 4. Anomaly Detection Logic
- A specialized routine is implemented to flag anomalies based on classification thresholds or reconstruction errors (depending on the task).

---

## 🧰 Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install the dependencies:
   ```bash
   pip install tensorflow numpy matplotlib scikit-learn
