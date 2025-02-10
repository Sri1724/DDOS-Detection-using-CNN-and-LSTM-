# DDOS-Detection-using-CNN-and-LSTM

# DDoS Attack Detection using Deep Learning

## 📌 Project Overview
This project focuses on detecting **DDoS (Distributed Denial-of-Service) attacks** using a hybrid deep learning model combining **CNN (Convolutional Neural Networks) and LSTM (Long Short-Term Memory)** networks. The goal is to improve accuracy while keeping computational complexity low.

## 🔍 Dataset
The dataset used contains network traffic features such as:
- Source & Destination IPs
- Packet and Byte Counts
- Flow Rates
- Protocol Type & Port Numbers
- Label Column (Three classes: **Benign, DDoS-PSH-ACK, DDoS-ACK**)

### Label Distribution:
- **Benign**: 49,971 samples
- **DDoS-PSH-ACK**: 25,069 samples
- **DDoS-ACK**: 24,960 samples

## 📑 Methodology
1. **Data Preprocessing**
   - Feature selection
   - Handling missing values
   - One-hot encoding for categorical features
2. **Model Architecture**
   - CNN extracts spatial features from network traffic
   - LSTM captures temporal patterns
   - Fully connected layers classify traffic as Benign or DDoS
3. **Training & Evaluation**
   - Split data into training & testing sets
   - Use **Cross-Entropy Loss** and **Adam Optimizer**
   - Performance metrics: **Accuracy, Precision, Recall, F1-score**

## ⚙️ Installation
### Prerequisites:
Ensure you have the following installed:
- Python 3.x
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Scikit-learn

## 🛠 Future Improvements
- Real-time DDoS detection integration
- Optimization for cloud deployment


