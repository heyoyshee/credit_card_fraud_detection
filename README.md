# Credit Card Fraud Detection Using Machine Learning

A beginner-friendly machine learning project that detects fraudulent credit card transactions, with a focus on handling **class imbalance** and avoiding **data leakage**.

> 🚧 **Status:** Work in progress. The full README will be updated when the project is complete.

## Dataset

- Source: [Credit Card Fraud Detection (Kaggle)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions, of which only 492 are fraud (0.17%)
- Features: `Time`, `V1`–`V28` (PCA-anonymized), `Amount`; target: `Class`
- The dataset file is not included in this repository because of its size. Download it from Kaggle and place `creditcard.csv` in the `dataset/` folder.

## Project Goals

- [x] Project setup and data loading
- [ ] Exploratory Data Analysis (EDA)
- [ ] Handle class imbalance
- [ ] Preprocessing without data leakage
- [ ] Train Logistic Regression, Decision Tree, Random Forest
- [ ] Evaluate with Precision, Recall, F1, PR-AUC, Confusion Matrix
- [ ] Compare models and conclude

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab

## Project Structure


## How to Run

1. Clone this repo
2. Download `creditcard.csv` from Kaggle into `dataset/`
3. Install dependencies: `pip install -r requirements.txt`
4. Open `notebooks/fraud_detection.ipynb` in Google Colab or Jupyter
