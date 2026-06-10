🥔 Potato Disease Classification using Deep Learning
📌 Overview

Potato crops are highly vulnerable to diseases such as Early Blight and Late Blight, which can significantly reduce yield and cause economic losses for farmers.

This project uses Convolutional Neural Networks (CNNs) and TensorFlow to automatically classify potato leaf images into different disease categories. The solution provides farmers with a fast and reliable way to detect diseases and take corrective action at an early stage.

🚀 Features

Automated potato leaf disease detection
Multi-class image classification
Data augmentation for improved generalization
TensorFlow-based CNN architecture
FastAPI backend for model serving
TensorFlow Lite optimization for edge deployment
ReactJS frontend for real-time predictions
Production-ready deployment architecture

🎯 Problem Statement

Early detection of potato diseases is critical for reducing crop damage and improving agricultural productivity.

This project aims to:

Detect diseases from potato leaf images
Classify healthy and infected plants
Assist farmers in taking preventive actions
Reduce economic losses caused by crop diseases

📊 Dataset

Source: PlantVillage Dataset

Classes :
Potato Early Blight
Potato Late Blight
Healthy Potato

Data Preprocessing :
Image resizing to 256 × 256
Dataset loading using TensorFlow image_dataset_from_directory
Batch processing using tf.data.Dataset
Normalization and caching for efficient training

🔄 Data Augmentation

To improve model robustness and prevent overfitting:

Random Horizontal Flip
Random Rotation
Random Zoom
Random Contrast Adjustments

🧠 Model Architecture

The model is built using a Convolutional Neural Network (CNN) consisting of:

Convolution Layers
Max Pooling Layers
ReLU Activation
Dropout Layers
Fully Connected Dense Layers
Softmax Output Layer

Training ConfigurationTraining Configuration

| Parameter     | Value                           |
| ------------- | ------------------------------- |
| Framework     | TensorFlow                      |
| Optimizer     | Adam                            |
| Loss Function | Sparse Categorical Crossentropy |
| Task          | Multi-Class Classification      |


📈 Model Training & Evaluation

The model was trained using TensorFlow and evaluated on validation and test datasets.

Performance metrics monitored:

Training Accuracy
Validation Accuracy
Training Loss
Validation Loss

Visualization includes:

Accuracy Curves
Loss Curves
Sample Predictions

⚡ Model Optimization

To support deployment on resource-constrained devices:

TensorFlow Lite Conversion
Model Quantization
Reduced Model Size
Faster Inference Performance

🏗 Deployment Architecture

Backend :
TensorFlow Serving
FastAPI

Frontend :
ReactJS

Workflow :
User Uploads Leaf Image
          │
          ▼
React Frontend
          │
          ▼
FastAPI Backend
          │
          ▼
TensorFlow Model
          │
          ▼
Disease Prediction
          │
          ▼
Result Displayed to User

🛠 Technology Stack

Deep Learning :
TensorFlow
Keras
CNN

Data Processing :
NumPy
Pandas
Matplotlib
tf.data.Dataset

Backend & MLOps :
FastAPI
TensorFlow Serving

Model Optimization :
TensorFlow Lite
Quantization

Frontend :
ReactJS

📷 Sample Prediction

Input: Potato Leaf Image
Output:

Prediction: Late Blight
Confidence: 98.7%

Prediction: Late Blight
Confidence: 98.7%

📌 Future Improvements

Mobile Application Integration
Real-Time Camera Detection
Multi-Crop Disease Classification
Cloud Deployment on AWS/GCP
Explainable AI (Grad-CAM Visualizations)

👨‍💻 Author

Siddhant Patil

GitHub: (https://github.com/siddhantpatilai-tech/dl_potatoDisease_Image_identifier?utm_source=chatgpt.com))

LinkedIn:(https://www.linkedin.com/in/siddhant-patil-669499400?utm_source=share_via&utm_content=profile&utm_medium=member_android))
