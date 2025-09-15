# Fraud Detection Model

**Built with Ensemble Learning, Hyperparameter Optimization, and Explainable AI (XAI)**

---

## Overview

This project focuses on **detecting fraudulent transactions** using advanced **Machine Learning techniques**.
Since fraud detection is a **highly imbalanced classification problem**, the model is designed to prioritize **Precision** and **F1-score** over just Accuracy to reduce false positives and ensure reliable fraud detection.

We use an **Ensemble Learning approach** combining:

* **Logistic Regression**
* **Random Forest**
* **XGBClassifier (Extreme Gradient Boosting)**

The models are fine-tuned with **hyperparameter optimization** and later enhanced with **Explainable AI (XAI)** to make predictions more interpretable for stakeholders.

---

## Project Structure

```
Task-1 Advanced Fraud Detection/
│
├── fraud_Preparation.ipynb       # Data cleaning, EDA, and feature engineering
├── Fraud_detection_build.ipynb   # Ensemble Learning + Hyperparameter optimization
├── Fraud_detection_XAI.ipynb     # Explainable AI (XAI) implementation
│
├── saved_models/                # Trained models saved for reuse
├── processed_data/              # Preprocessed datasets saved after each stage
│
├── requirements.txt                # Dependencies
├── README.md                       # Project documentation
```

---

##  Key Features

- **Exploratory Data Analysis (EDA):** Identifying patterns, multi-collinearity, and class imbalance.
- **Feature Engineering:** Creating and transforming features to boost performance.
- **Ensemble Learning:** Combining Logistic Regression, Random Forest, and XGBoost.
- **Hyperparameter Tuning:** GridSearchCV for model optimization.
- **Evaluation Metrics:** Focus on **Precision** and **F1-score** to minimize fraud misclassification.
- **Explainable AI (XAI):** SHAP for interpretability of model predictions.
- **Modular Workflow:** Each notebook builds upon the previous, with saved datasets and models for efficiency.

---

##  Installation

1. Clone this repository

```bash
git clone https://github.com/Onome-Joseph/Flexisaf/Task-1 Advanced Fraud Detection.git
cd Task-1 Advanced Fraud Detection
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook
---

## Usage

1. **Data Preprocessing & EDA**

   * Run `fraud_Preparation.ipynb` to clean and prepare the dataset.
   * The processed dataset is saved for later use.

2. **Model Training & Hyperparameter Tuning**

   * Run `Fraud_detection_build.ipynb` to train models, fine-tune hyperparameters, and build the ensemble model.
   * Trained models are saved for reuse.

3. **Explainable AI (XAI)**

   * Run `Fraud_detection_XAI.ipynb` to interpret model predictions using SHAP.
