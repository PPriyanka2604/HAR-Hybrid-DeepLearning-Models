# Human Activity Recognition using Hybrid Deep Learning Models (MHEALTH Dataset)

This repository contains my Human Activity Recognition (HAR) project developed during my internship at **IIITDM Kurnool**. The project focuses on building multiple **Deep Learning** and **Hybrid Deep Learning** models to classify human activities using the **MHEALTH dataset**, a multi-sensor dataset containing accelerometer, gyroscope, and ECG data.

The work includes:
- **7 Single Deep Learning Models**
- **Multiple 2-Model Hybrid Architectures**
- **Multiple 3-Model Hybrid Architectures**
- All models trained and evaluated in **Google Colab**

---

## 📌 Project Overview

Human Activity Recognition (HAR) is widely used in:
- Healthcare & medical monitoring  
- Wearable devices  
- Fitness and rehabilitation  
- Smart environments  

The MHEALTH dataset provides continuous sensor signals recorded at **50 Hz**, making it ideal for time-series deep learning models such as CNNs, LSTMs, GRUs, Transformers, and WaveNet.

---

## 🧠 Models Implemented

### 🔹 Single Models (7)
- CNN  
- LSTM  
- GRU  
- Transformer  
- WaveNet  
- RBFNN  
- Dilation CNN  

### 🔹 2-Model Hybrid Architectures
Examples:
- CNN + LSTM  
- CNN + GRU  
- CNN + WaveNet  
- GRU + Transformer  
- Transformer + RBFNN

---

### 🔹 3-Model Hybrid Architectures
Examples:
- CNN + LSTM + WaveNet  
- CNN + GRU + Transformer  
- CNN + Dilation CNN + RBFNN  
- GRU + Dilation CNN + Transformer  

---

## 🏆 Best Performing Model

**WaveNet** achieved the **highest test accuracy and robustness**, due to its use of:
- Dilated causal convolutions  
- Excellent temporal feature extraction  
- Ability to learn long-range patterns in sensor data  

Hybrid models also showed strong improvements over single models.

---

HAR_Project/
│
├── single_models/
├── hybrid_2_models/
├── hybrid_3_models/
└── requirements.txt


Each folder contains the Colab notebooks (`.ipynb`) for each model.

---

## ▶️ How to Run

1. Open any `.ipynb` notebook  
2. Upload it to **Google Colab**  
3. Install dependencies:



pip install -r requirements.txt


4. Run all cells to train and evaluate the model  
5. Visualizations (accuracy, loss, confusion matrix) will be generated automatically

---

## 📈 Key Results

- Hybrid models outperform individual models  
- WaveNet provides the highest accuracy  
- 3-model hybrids give stable, high-performance results  
- Models are effective for wearable sensor analysis and healthcare activity monitoring  

---

## ⭐ Author

**Pabbathi Priyanka**  
Deep Learning | Human Activity Recognition | Hybrid Models  
IIITDM Kurnool – Internship Project  

---

## ⭐ If you like this project, please give the repository a star!
## 📁 Folder Structure

