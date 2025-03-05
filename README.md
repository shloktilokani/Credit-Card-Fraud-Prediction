# Fraud Detection Analysis
![Preview](https://github.com/shloktilokani/Credit-Card-Fraud-Prediction/blob/main/res/Recording%202025-03-05%20113403.gif)
## Overview
This project analyzes financial transaction data to detect fraudulent activities using machine learning techniques. The goal is to build a classification model that accurately distinguishes fraudulent transactions from legitimate ones.

## Dataset
The dataset consists of various financial transaction records with features such as:
- `is_fraud`: Target variable (1 for fraud, 0 for legitimate transactions)
- `amt`: Transaction amount
- `gender`: Customer gender
- `job`: Job category of the customer
- `category`: Type of transaction

### Download Dataset
You can download the dataset from Kaggle using the following link:  
[Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)

## Methodology
1. **Data Preprocessing**
   - Load data using `pandas`
   - Select relevant columns
   - Handle missing values and categorical encoding
   - Scale features using `StandardScaler`

2. **Model Training**
   - Split the dataset into training and testing sets using `train_test_split`
   - Train a Logistic Regression model using `sklearn.linear_model`

3. **Evaluation Metrics**
   - `accuracy_score` to measure overall correctness
   - `confusion_matrix` to understand classification performance
   - `classification_report` for precision, recall, and F1-score

## Results
- The Logistic Regression model was trained and evaluated.
- Performance metrics indicate the model's effectiveness in fraud detection.
- Visualizations were generated using `matplotlib` and `seaborn` to analyze feature distributions and model performance.

## Dependencies
The project requires the following Python libraries:
```bash
pip install pandas scikit-learn matplotlib seaborn
