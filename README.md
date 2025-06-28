# Brain Tumor Detection with CNN 🧠

This repository contains a **Convolutional Neural Network (CNN)** implementation using TensorFlow and Keras to classify MRI images for **brain tumor detection**.

## ✨ Features

* Counts and organizes MRI images into training, validation, and testing sets 📂
* Data preprocessing with augmentation for training data
* CNN model architecture with dropout for regularization
* Uses early stopping and model checkpointing to save the best model automatically
* Graphical visualization of accuracy and loss
* Single image prediction with visualization

## ⚙️ Setup

Upload and extract your dataset:

```python
!unzip /content/archive.zip
```

Ensure your extracted folder has `yes/` and `no/` folders for classification.

## 🧪 Running Training

Execute the provided cells in order:

* Count images per class
* Split data into train/val/test (70/15/15)
* Define CNN model
* Compile and fit model with early stopping and checkpoint
* Visualize accuracy and loss graphs
* Evaluate model accuracy on test data
* Predict on a single MRI image

## 🏗️ Model

* 4 Convolutional layers with ReLU activations
* MaxPooling layers for downsampling
* Dropout layers to prevent overfitting
* Dense output with sigmoid for binary classification

## 📊 Results

The model achieves **\~74% accuracy** on the test dataset.

## 🔍 Predicting on Single Image

The notebook allows uploading an MRI image and predicting:

* "The person has brain tumor" if detected
* "The person does not have brain tumor" if not detected

---

This project is useful for learning **medical image classification, CNN workflows, and data preparation pipelines** in deep learning projects. Let me know if you need an inference notebook or further documentation next!
