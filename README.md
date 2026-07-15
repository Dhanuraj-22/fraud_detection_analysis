# Fraud Detection Analytics

Intern ID:CITS5330

Name:Dhanushree R

Duration:4 weeks

## Objective

To detect fraudulent online payment transactions using Machine Learning by analyzing transaction details and customer account information.

## Technologies

Python

Google Colab

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

## Dataset

Online Payments Fraud Detection Dataset

Features:
- Step
- Transaction Type
- Amount
- Old Balance (Sender)
- New Balance (Sender)
- Old Balance (Receiver)
- New Balance (Receiver)
- Flagged Fraud Indicator

Target:
- isFraud (0 = Genuine Transaction, 1 = Fraudulent Transaction)

## Algorithm

Logistic Regression

## Project Workflow

1. Import the required libraries.
2. Load the Online Payments Fraud Detection dataset.
3. Remove unnecessary columns.
4. Encode categorical transaction types.
5. Perform Exploratory Data Analysis (EDA).
6. Visualize fraud and genuine transaction distribution.
7. Generate a correlation heatmap.
8. Split the dataset into training and testing sets.
9. Train the Logistic Regression model.
10. Predict fraudulent transactions.
11. Evaluate the model using Accuracy, Confusion Matrix, and Classification Report.
12. Test the model with a new transaction.

## Output

- Fraud Distribution Graph
- Correlation Heatmap
- Model Accuracy
- Confusion Matrix
- Classification Report
- Actual vs Predicted Results
- Fraud Prediction

## Future Scope

- Improve accuracy using Random Forest, XGBoost, or LightGBM.
- Detect fraud in real time using streaming transaction data.
- Deploy the model as a web application using Streamlit or Flask.
- Integrate with banking or payment gateway systems for live fraud monitoring.

## Conclusion

This project demonstrates how Machine Learning can identify fraudulent online payment transactions by analyzing transaction patterns. It helps financial institutions and payment platforms reduce fraud, improve security, and protect customers from financial losses.
