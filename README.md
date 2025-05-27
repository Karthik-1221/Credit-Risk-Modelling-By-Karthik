💳 Lauki Finance: Credit Risk Modelling

This project is a Streamlit web application that simulates credit risk assessment for loan applicants. By inputting a variety of financial and demographic parameters, users can assess the likelihood of default using a machine learning classification model.

🔗 Live App: credit-risk-modelling-by-karthik.streamlit.app

🔍 Overview

Lauki Finance models how financial institutions assess an individual's creditworthiness. This user-friendly Streamlit app allows users to input:

    Age

    Income

    Loan Amount

    Tenure

    Credit Utilization Ratio

    DPD (Days Past Due)

    Delinquency Ratio

    and more...

The app then uses a trained classification model to output whether the applicant is high risk or low risk.
✨ Features

✅ Real-time credit risk scoring
✅ Dynamic calculation of Loan to Income Ratio
✅ Clean, responsive UI with dark theme
✅ Dropdown and numeric inputs for quick experimentation
✅ Supports multiple loan purposes and types
🧰 Tech Stack

    Frontend: Streamlit

    Backend: Python, Scikit-learn

    Modeling: Logistic Regression / Random Forest (based on training pipeline)

    Data Processing: Pandas, NumPy

    Model Deployment: Streamlit Cloud

    Model Serialization: Joblib

🧠 Model Details

    This project uses a classification algorithm (e.g., Logistic Regression or Random Forest) trained on synthetic or anonymized credit data.

Features used in model:

    Age

    Income

    Loan Amount

    Loan to Income Ratio

    Loan Tenure

    Average DPD

    Delinquency Ratio

    Credit Utilization

    Open Loan Accounts

    Residence Type

    Loan Purpose

    Loan Type

    The model was trained offline and exported using joblib, then loaded in the Streamlit app for prediction.
