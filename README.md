# 🚨 Network Traffic Anomaly Detection using Variational Autoencoder (VAE)

## 📌 Overview
This project implements a deep learning-based anomaly detection system for
network traffic using a Variational Autoencoder (VAE). The model learns normal
traffic patterns and identifies anomalies based on reconstruction error.

The system is designed to detect unusual or potentially malicious network
activities by analyzing flow-based network traffic data.

---

## 🎯 Objectives
- Learn normal network traffic behavior
- Detect anomalies using reconstruction error
- Improve intrusion detection using deep learning
- Automate abnormal traffic identification

---

## 🧠 Methodology

1. Data Preprocessing
   - Load network traffic dataset
   - Handle missing values
   - Normalize numerical features
   - Split data into training and testing sets

2. Model Architecture
   - Encoder network
   - Latent space representation
   - Decoder network
   - Reconstruction loss + KL divergence loss

3. Training
   - Train VAE on normal traffic data
   - Optimize using backpropagation

4. Anomaly Detection
   - Compute reconstruction error
   - Set threshold for anomaly detection
   - Classify high-error samples as anomalies

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📂 Project Structure
