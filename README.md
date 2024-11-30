
# Loan Prediction Project - Submitted by me as part of a school project (Year 2)

## Overview

This project is aimed at building a predictive model for loan approval decisions for a bank. Using historical customer data, 
various data mining techniques were applied to understand the key factors influencing loan decisions and to develop a deep 
learning model for predictions.

## Features

- Data exploration and visualization to identify correlations and trends.
- Implementation of clustering for additional insights.
- Development of a neural network model using PyTorch.
- Evaluation of model performance using metrics like accuracy, precision, and AUC-ROC.

## Dataset

The dataset includes 5000 customer records with attributes such as:
- Age, Income, Family size, and Education level.
- Indicators for mortgage, securities account, CD account, and credit card use.
- A binary target variable indicating loan approval (1 = Approved, 0 = Denied).

## Results

- Achieved an accuracy of 99% and a precision of 98.03%.
- ROC curve with an Area Under Curve (AUC) of 0.99, indicating excellent classification performance.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/IleneBiju7/LoanPredictionProject.git
   ```

2. Navigate to the project directory and install dependencies:
   ```bash
   cd LoanPredictionProject
   pip install -r requirements.txt
   ```

4. Update the file path in the notebook.
   ```bash
   file_path = "./data/UniversalBank.csv"
   data = pd.read_csv(file_path)
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/Data_Mining_Project.ipynb
   ```

## Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- PyTorch
