🧠 Brain Tumor Classification using MobileNetV2

A deep learning–based medical image classification system that detects the presence of brain tumors from MRI scans using transfer learning with MobileNetV2.

📌 Project Overview

This project builds a binary image classifier that predicts whether a brain MRI image contains a tumor or not.

The model is trained using transfer learning to achieve high accuracy while remaining lightweight and efficient.

🎯 Objectives

Classify MRI images into:

✅ Tumor Present

❌ No Tumor

Use a lightweight CNN suitable for low-memory GPUs

Optimize training for GTX 1650 (4GB VRAM)

Save all outputs inside the project directory

🧠 Model Architecture

Base Model: MobileNetV2 (Pretrained on ImageNet)

Transfer Learning (Feature extraction)

Custom Dense Layers

Sigmoid output (Binary classification)

📂 Dataset

Dataset used:

Brain MRI Images for Brain Tumor Detection (Kaggle)

Classes:

yes (Tumor)

no (Normal)

Dataset split:

80% Training

20% Validation
📊 Results

Achieves high training and validation accuracy

Lightweight model with fast inference

Suitable for real-time classification systems

<img width="1367" height="566" alt="image" src="https://github.com/user-attachments/assets/0552412f-71cf-41a2-8bf9-71838e8133e9" />
