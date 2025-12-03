# Potato-plant-disease-detection
This repository contains the source code for an end-to-end Deep Learning project designed to classify potato leaf diseases. The project moves beyond just model training to include a full-stack web and mobile application deployment. It uses a Convolutional Neural Network (CNN) to detect "Early Blight" and "Late Blight" in potato plants from images.

# Potato Disease Classification

## 📌 Overview
This project uses Deep Learning to classify potato leaf diseases from images. Utilizing a Convolutional Neural Network (CNN) built with TensorFlow/Keras, the model identifies whether a plant is healthy or suffering from Early/Late Blight.

## 📂 Dataset
The model is trained on the **PlantVillage** dataset.
* **Classes:**
    * Early Blight
    * Late Blight
    * Healthy
* **Image Specs:** 256x256 px, RGB.

## 🛠️ Technologies
* python 3.8 and higher
* tensorFlow==2.5.0
* matplotlib
* fastapi
* uvicorn
* pillow
* tensorflow-serving-api==2.5.0
* numPy

## ⚙️ Model Architecture
A custom CNN architecture comprising:
* Data Augmentation layers (Flip, Rotation)
* 6 Conv2D & MaxPooling layers
* Dense layers for final classification (Softmax output)

## 🚀 Performance
* **Accuracy:** ~98% on the test set.
* **Epochs:** 50

## 📥 Setup & Usage
1.  Install dependencies: `pip install tensorflow matplotlib numpy`
2.  Place the `PlantVillage` dataset in the root directory.
3.  Run the Jupyter Notebook to train the model.
4.  The model is automatically saved to the `../models` directory with versioning.
