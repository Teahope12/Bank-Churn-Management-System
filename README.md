# Bank-Churn-Management-System
It is a Flask-based web application designed to predict customer churn for a bank. It uses a machine learning model trained on real customer data to provide risk assessment, recommendations, and visual analytics.
# Customer Churn Prediction for Bank

## Project Overview
This project is a Flask-based web application designed to predict customer churn for a bank. It uses a machine learning model trained on real customer data to provide risk assessment, recommendations, and visual analytics.

## Features
- **Web Interface:** A user-friendly interface for inputting customer data and receiving churn predictions.
- **Model Training:** A script (`train_model.py`) that trains a Random Forest model on the customer dataset.
- **Risk Assessment:** The application provides risk levels and recommendations based on customer data.
- **Visualizations:** Various visualizations and summary statistics for exploratory data analysis.

## Tech Stack
- **Backend:** Flask
- **Machine Learning:** scikit-learn, pandas, numpy, joblib
- **Frontend:** Bootstrap for a responsive and modern UI

## Dataset
The dataset (`churn.csv`) contains 10,000 customer records with the following features:
- `RowNumber`, `CustomerId`, `Surname`
- `CreditScore`
- `Geography`
- `Gender`
- `Age`
- `Tenure`
- `Balance`
- `NumOfProducts`
- `HasCrCard`
- `IsActiveMember`
- `EstimatedSalary`
- `Exited` (churn label)

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Customer_churn_prediction_for_bank
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Train the model:
   ```bash
   python train_model.py
   ```
4. Run the Flask application:
   ```bash
   python app.py
   ```
5. Open your web browser and navigate to `http://localhost:5000` to access the application.

## Usage Examples
- **Input Customer Data:** Use the web interface to input customer details such as credit score, geography, gender, age, tenure, balance, number of products, credit card status, active membership, and estimated salary.
- **Get Predictions:** Submit the form to receive a churn prediction, risk level, and recommendations.

## Visualizations
The `visualizations` directory contains various PNG files and a summary statistics CSV file for exploratory data analysis. These visualizations help in understanding the dataset and the model's performance.
