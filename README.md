# ✨ Customer Churn Prediction (Bank Customers)

Predicting which bank customers are likely to leave so the business can **take action before they churn**.

## 📌 Project Overview

This project uses the classic *Churn Modelling* dataset to build a classification model that predicts whether a customer will exit the bank (churn) or stay.  
The focus is on building a clear end‑to‑end pipeline: data preparation, model training, evaluation, and feature importance analysis.[web:52][web:54]

## 🧾 Dataset

- Source: Churn Modelling Dataset (bank customers)
- Rows: 10,000 customers  
- Target: `Exited` (1 = customer left, 0 = customer stayed)
- Example features:
  - `CreditScore`, `Age`, `Balance`
  - `Geography` (France, Spain, Germany)
  - `Gender` (Male, Female)
  - `Tenure`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`, `EstimatedSalary`[web:54][web:58]

Files in this repo:
- `Task 3.ipynb` – full notebook (cleaning, modelling, evaluation)
- `Churn_Modelling.csv` – dataset used in the notebook

## ⚙️ Tech Stack

- Language: Python  
- Libraries:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn` (preprocessing, train‑test split, RandomForestClassifier, metrics)[web:54]

## 🔁 Workflow

1. Load and inspect the dataset  
2. Clean data (remove unused columns, handle any issues)  
3. Encode categorical columns (`Geography`, `Gender`)  
4. Split into train and test sets  
5. Train a classification model (Random Forest)  
6. Evaluate using accuracy and classification report  
7. Analyze feature importance to understand what drives churn[web:54][web:55]

## 📊 Model & Results

- Model: Random Forest Classifier  
- Task: Binary classification – predict `Exited` (0/1)  
- Evaluation:
  - Accuracy score on test data
  - Precision, recall, F1‑score for both churn and non‑churn classes  
- Feature importance:
  - Shows which variables (e.g., **Age**, **Balance**, **NumOfProducts**, **IsActiveMember**) contribute the most to churn predictions.[web:55][web:58]

You can explore all steps and outputs directly in `Task 3.ipynb`.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Faraz-jehangiri/Customer-Churn-Prediction.git
   cd Customer-Churn-Prediction
