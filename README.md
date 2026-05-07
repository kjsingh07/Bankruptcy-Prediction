# Hybrid Stacking Model for Corporate Bankruptcy Prediction

## Overview
This project focuses on predicting corporate bankruptcy using financial ratio data and advanced machine learning techniques. A hybrid stacking model is developed to improve predictive performance on imbalanced financial datasets.

The model leverages ensemble learning by combining multiple base learners with a meta-learner, achieving high accuracy and strong generalization.

---

## Dataset
- **Source:** UCI Machine Learning Repository  
- **Dataset:** Polish Companies Bankruptcy Dataset  
- **Description:**  
  Contains financial ratios of companies over multiple years, labeled as bankrupt or non-bankrupt.

- Link: https://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data

---

## Methodology

### 1. Data Preprocessing
- Handling missing values  
- Feature scaling and normalization  
- Class imbalance handling using **SMOTE**

### 2. Feature Engineering
- Statistical feature selection  
- Dimensionality reduction (Autoencoders)

### 3. Model Architecture
- **Base Models:**
  - XGBoost
  - Neural Network
- **Meta-Learner:**
  - Logistic Regression

- Implemented a **stacking ensemble** to combine predictions and improve robustness.

---

## Results
- Accuracy: ~99%  
- ROC-AUC: ~0.995  
- Improved minority class detection compared to standalone models

---

## Key Features
- Handles highly imbalanced financial data  
- Combines tree-based and deep learning models  
- Uses stacking for improved generalization  
- End-to-end ML pipeline from preprocessing to evaluation  

---

## Tech Stack
- Python  
- scikit-learn  
- XGBoost  
- TensorFlow / PyTorch  
- Pandas, NumPy  
