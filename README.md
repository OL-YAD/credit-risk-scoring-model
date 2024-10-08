# Credit Risk Scoring Model

## Overview
This project develops a credit scoring model for Bati Bank's buy-now-pay-later service in partnership with an eCommerce company. The model aims to assess customer creditworthiness and predict the likelihood of default.

## Business Context
Bati Bank, a leading financial service provider, is partnering with an eCommerce company to offer a buy-now-pay-later service. This project creates a Credit Scoring Model using data provided by the eCommerce platform to evaluate potential borrowers.


## Project Structure

```plaintext

credit-risk-scoring-model/
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows/
│       └── unittests.yml   # GitHub Actions
├── .gitignore              # files and folders to be ignored by git
├── requirements.txt        # contains dependencies for the project
├── README.md               # Documentation for the projects
├── src/
│   └── __init__.py
├── notebooks/
│   ├── __init__.py
|   |──preprocessing.ipynb              # Jupyter notebook for data cleaning and processing 
|   ├──eda_analysis.ipynb               # Jupyter notebook for customer purchasing behavior analysis 
|   ├──ml_preprocess.ipynb              # Jupyter notebook for  data preparation for model training 
|   ├──ml_modelling.ipynb               # Jupyter notebook for Regression model training 
|   |──dl_modelling.ipynb               # Jupyter notebook for LSTM model training 
│   └── README.md                       # Description of notebooks directory 
├── tests/
│   └── __init__.py
└── scripts/
    ├── __init__.py
    ├── preprocessing.py            # script for data processing, cleaning
    ├── eda_analysis.py             # Script for customer EDA analysis of customer purchasing behavior
    ├── ml_preprocess.py            # script for data processing for machine learning model
    ├── ml_modelling.py             # script for regression model training
    |──  dl_modelling.py            # script for LSTM model training 
    └── README.md                   # Description of scripts directory
    
```


## Setup

1. Clone the repository:
   ```
   git clone https://github.com/OL-YAD/rossmann-pharmaceuticals-sales-forecast.git
   cd rossmann-pharmaceuticals-sales-forecast
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```


## Model Development Process
1. Exploratory Data Analysis (EDA)
2. Feature Engineering
3. Default Estimator Creation
4. Model Selection and Training
5. Model Evaluation
6. API Development for Model Serving