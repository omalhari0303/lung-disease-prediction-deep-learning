# Lung Disease Prediction Using Deep Learning

A deep learning-based web application for detecting and classifying lung diseases from chest X-ray images.

The system uses a Convolutional Neural Network (CNN) trained on chest X-ray images and provides predictions through a Flask web application.

## 🩺 Supported Classes

The model classifies chest X-ray images into four categories:

- COVID-19
- Normal
- Pneumonia
- Tuberculosis

## 🚀 Features

- Chest X-ray image upload
- Deep learning-based disease classification
- Four-class prediction
- Flask-based web interface
- Prediction result display
- Model performance visualization
- Interactive charts and performance pages
- Simple and user-friendly interface

## 🧠 Technology Stack

### Machine Learning
- Python
- TensorFlow
- Keras
- NumPy

### Web Application
- Flask
- HTML
- CSS
- JavaScript
- Bootstrap

### Development Tools
- Jupyter Notebook
- VS Code
- Git & GitHub

## 📁 Project Structure

```text
lung-disease-prediction-deep-learning/
│
├── app.py
├── lung.h5
├── README.md
├── .gitignore
│
├── templates/
│   ├── first.html
│   ├── login.html
│   ├── index.html
│   ├── prediction.html
│   ├── performance.html
│   └── chart.html
│
├── static/
│   ├── assets/
│   └── tests/
│
└── model/
    └── DATASET/
