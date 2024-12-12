# Credit Card Fraud Detection System

## Project Overview

With the surge in online transactions, credit card fraud has become a significant concern, costing billions of dollars annually and affecting both consumers and businesses. Effective fraud detection systems are crucial to shield clients from monetary losses and unauthorized transactions while reducing the risk of default.

This project leverages machine learning techniques to detect fraudulent activities in credit card transactions. By analyzing large datasets, it identifies fraud patterns, enabling early detection and prevention. The focus is on building a reliable system that mitigates fraud and enhances trust in financial systems.

This project stands out due to its meticulous approach to feature selection and model optimization. From an extensive dataset containing 120 features, we conducted a detailed analysis to identify the most relevant attributes, streamlining the data for efficient processing and reducing noise. Unlike many standard implementations, we explored and compared a variety of machine learning algorithms to determine the best fit for the task. Most notably, by applying advanced hyperparameter tuning techniques, we achieved a remarkable accuracy improvement from 88.26% to 98.37%. This significant enhancement is critical given the financial implications of the problem, where even minor inaccuracies can lead to substantial monetary losses and compromised trust. This project exemplifies a thoughtful, data-driven approach to solving real-world challenges in fraud detection.

---

## Problem Statement

The rise of e-commerce has increased the incidence of credit card fraud, necessitating the development of effective fraud detection systems to minimize financial losses for institutions and customers.

---

## Datasets

### Dataset 1: Credit Card Fraud Detection (Kaggle)

- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Details:**
  - Originates from the research lab of Université Libre de Bruxelles.
  - Contains 28 encrypted features using PCA.
  - Optimized for accurate predictions, though it lacks descriptive feature labels.

### Dataset 2: Credit Card Fraud Detection (Kaggle)

- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/mishra5001/credit-card)
- **Details:**
  - Collected as part of a social experiment by a financial institution.
  - Includes 120 features representing diverse customer attributes.
  - Offers robust classification accuracy with distinct impacts across models.

---

## Algorithms Used

Several machine learning algorithms were evaluated to detect fraudulent transactions:

- Logistic Regression
- AdaBoost Classifier
- Random Forest (Selected as the most accurate)
- Decision Tree
- Linear Discriminant Analysis
- Naive Bayes Classifier
- XGBoost Classifier

---

## Feature Extraction

Feature extraction is a vital step in transforming raw data into a suitable format for processing:

- **Correlation Matrix:** Identifies relationships between variables, eliminates redundant features, and improves model performance.
- Helps reduce multicollinearity and select predictive features, streamlining the model for efficiency.

---

## Implementation

### Model Persistence

- **Pickle Module:** Used for serializing and deserializing machine learning models, allowing them to be saved and reused without retraining.

### Web Framework

- **Flask:** A lightweight Python framework utilized to build the web application interface for presenting insights and results.

### User Interface (UI)

- Provides interactive insights into credit card defaulters, including demographics, transaction history, and payment behavior.
- Features charts, graphs, and tables for visualizing data, enhancing user experience.

---

## Results

The Random Forest algorithm emerged as the most effective model, achieving:

- **Accuracy:** 98.37%
- **Precision:** 98.98%
- **Recall:** 80.31%
- **F1-Score:** 88.67%

---

## How to Run the Project

1. **Clone the repository**:

   ```bash
   git clone <repository_url>

   ```

2. **Download the pre-trained model from the following link:**:

   ```bash
   https://drive.google.com/file/d/1-i6JctkggEnWqeoRd0mS-RoH7SGHwEAV/view

   ```

3. **Run the Flask application**:
   ```bash
   python app.py
   ```
