# Customer Churn Prediction
This project uses the Telco Customer Churn dataset to predict whether a customer will leave a telecom service. The project applies data preprocessing, one-hot encoding, and a Random Forest Classifier to identify at-risk customers, achieving an F1 score 0.79. This helps businesses take proactive retention actions.

## Overview
This project predicts whether a customer will churn (leave the service) based on their demographic, account, and usage data.  
The dataset used is the **Telco Customer Churn dataset**, which contains information such as contract type, monthly charges, tenure, and services subscribed.

The goal is to help businesses identify at-risk customers and take proactive retention actions.

---

## Features of the Project
- **Exploratory Data Analysis (EDA):**
  - Visualizations of churn distribution.
  - Correlation heatmaps for feature importance.
- **Data Preprocessing:**
  - Handling missing values.
  - Encoding categorical variables using one-hot encoding.
  - Splitting data into training and testing sets.
- **Modeling:**
  - Random Forest Classifier for churn prediction.
  - Evaluation using Accuracy, Precision, Recall, and F1 Score.
- **Results:**
  - Achieved an F1 score of ~0.79 (varies by run and tuning).

---

## Tech Stack
- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Jupyter Notebook**

---

## Project Structure
    Customer Chrun
      ├── Dataset/                 # Dataset (not included here, link below)
      ├── Notebooks/               # Jupyter notebooks with code
      │  └── Customer_Churn.ipynb
      ├── requirements.txt         # Required Python libraries

## Install dependencies

pip install -r requirements.txt

## Dataset

- The project uses the [Telco Customer Churn dataset](https://www.kaggle.com/blastchar/telco-customer-churn).  
- Place the dataset CSV inside the `data/` folder before running the notebooks.
