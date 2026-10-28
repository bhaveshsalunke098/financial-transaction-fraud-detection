# Financial Transaction Fraud Detection Using Machine Learning

## Overview
A machine learning project that analyzes financial transactions and predicts potentially fraudulent activity. It includes exploratory data analysis, data preprocessing, model training, evaluation, and an interactive Streamlit application for predictions.

## Features
- Exploratory Data Analysis (EDA) and transaction visualizations
- Numerical feature scaling and categorical feature encoding
- Logistic Regression with balanced class weights
- Model evaluation using accuracy, precision, recall, F1-score, and a confusion matrix
- Interactive Streamlit application for transaction predictions

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Streamlit
- Joblib

## Project Structure

```text
financial-transaction-fraud-detection/
├── analysis_model.ipynb
├── fraud_detection.py
├── fraud_detection_pipeline.pkl
├── requirements.txt
├── .gitignore
└── README.md
```

## Getting Started

### Prerequisites
- Python
- pip

### Installation

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   cd financial-transaction-fraud-detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python -m streamlit run fraud_detection.py
   ```

## Dataset
The dataset is not included in this repository because of its large file size. Obtain the dataset from its original source and update the notebook's file path if necessary.

## Model Evaluation
The model is evaluated using accuracy, precision, recall, F1-score, and a confusion matrix. Refer to the notebook for the measured results and limitations, including false-positive predictions.

## Disclaimer
This project is intended for educational purposes. Further evaluation and improvement are necessary before using it in a real-world fraud detection system.
