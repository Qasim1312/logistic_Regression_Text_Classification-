# Logistic Regression for Hallucination Detection

## Overview

This project implements a **binary classification model** using **Logistic Regression** to detect hallucinated summaries.

## Dataset

- **XSum Hallucination Dataset**
- Uses the `summary` field as input and `is_factual` as labels.

## Features Implemented

- **Data Preprocessing**
  - Tokenization & Stopword Removal
  - Bag-of-Words Feature Extraction
  - Manual Train-Test Split

- **Logistic Regression (Implemented from Scratch)**
  - Uses **Gradient Descent** for optimization.
  - Includes **Cross-Validation** to evaluate robustness.

- **Evaluation Metrics**
  - Accuracy, Precision, Recall, F1 Score
  - Confusion Matrix for Performance Analysis
  - Error Analysis on Misclassified Examples

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_GITHUB_USERNAME/NLP_Logistic_Regression_Text_Classification.git
   cd NLP_Logistic_Regression_Text_Classification

2. Install dependencies:
    pip install pandas numpy nltk
    
3. Run the notebook:
   jupyter notebook logistic_regression_hallucination.ipynb
