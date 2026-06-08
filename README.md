Credit Card Fraud Detection
1. Introduction
Traditional fraud detection systems often fail to identify suspicious activities quickly due to the massive amount of transaction data. Therefore, automated fraud detection systems are essential for improving financial security.

This project uses data analysis and machine learning techniques to study transaction behavior and identify factors related to fraudulent transactions.

2. Problem Statement
Financial institutions and online payment systems process millions of credit card transactions every day. Among these transactions, some are fraudulent and unauthorized, leading to major financial losses for both customers and banks.

Due to the huge volume of transaction data, manually identifying fraudulent activities is difficult, time-consuming, and inefficient. Fraudulent transactions often occur within seconds, making it essential to detect suspicious activities automatically and accurately.

Incorrect fraud detection decisions can result in:
Financial losses for banks and customers
Unauthorized transactions
Poor fraud risk management
Reduced customer trust and security
Therefore, there is a need for an automated system that can analyze transaction data, identify unusual patterns, and help detect fraudulent credit card transactions.

This project focuses on Exploratory Data Analysis (EDA), Linear Regression, and Dashboard Visualization to understand transaction behavior and identify factors influencing fraud detection.

3. Objectives
The main objective of this project is to perform Exploratory Data Analysis, build a Linear Regression model, and create an interactive dashboard for fraud analysis.

Specific Objectives
Load and understand the dataset.
Perform data cleaning and preprocessing.
Analyze transaction behavior using statistical methods.
Compare normal and fraudulent transactions.
Identify high-risk transaction patterns.
Visualize relationships among features.
Build a Linear Regression model.
Evaluate model performance.
Create an interactive dashboard using Plotly.
Generate insights to support fraud prevention.
Dataset Features
Column Name	Description
Time	Time elapsed between transactions
Amount	Transaction amount
V1 – V28	Anonymized transaction features
Class	Target variable (0 = Normal, 1 = Fraud)
Removed Columns
The following types of columns were removed:

Duplicate transaction records
Unnecessary identifiers
Highly sparse columns
Irrelevant metadata columns
These columns were removed to simplify analysis and improve model performance.

5. Technologies Used
Technology	Purpose
Python	Programming Language
Pandas	Data manipulation
NumPy	Numerical operations
Matplotlib	Data visualization
Seaborn	Statistical visualization
Scikit-learn	Machine learning
Plotly	Interactive dashboard
Jupyter Notebook	Development environment
6. Methodology
6.1 Data Collection
The dataset was downloaded from Kaggle and loaded into Python using the Pandas library.

6.2 Data Cleaning and Preprocessing
The following preprocessing steps were performed:

Checked missing values
Removed duplicate records
Verified data types
Prepared dataset for analysis
6.3 Descriptive Statistics
Statistical analysis was performed to understand transaction behavior.

Calculations Included
Average transaction amount
Fraud vs normal transaction count
Transaction distribution
Feature variation analysis
7. Exploratory Data Analysis (EDA)
Exploratory Data Analysis helps understand patterns and relationships in the dataset.

7.1 Fraud Distribution Analysis
Fraudulent transactions were compared with normal transactions.

Observation
The dataset is highly imbalanced because fraud transactions are very small compared to normal transactions.

7.2 Transaction Amount Analysis
Transaction amounts were analyzed to identify suspicious patterns.

Observation
Fraudulent transactions often show unusual transaction amounts compared to normal transactions.

7.3 Time-Based Analysis
Transaction time was analyzed to identify unusual activity periods.

Observation
Certain time intervals showed increased fraud activity.

7.4 Correlation Analysis
A correlation heatmap was generated to identify relationships among features.

Observation
Some anonymized features showed strong correlation with fraud transactions.

8. Data Visualization
Different visualizations were used for better understanding of transaction patterns.

Visualizations Used
<img width="657" height="488" alt="image" src="https://github.com/user-attachments/assets/3647e19a-2419-4ef1-84fe-d9d26ad24e58" />
<img width="1295" height="463" alt="image" src="https://github.com/user-attachments/assets/0fb443d8-ed61-41f2-9c9d-c71a8f85a566" />
<img width="1355" height="487" alt="image" src="https://github.com/user-attachments/assets/b7dbc54a-71b2-4172-98ab-254c2c5f6153" />
<img width="1198" height="463" alt="image" src="https://github.com/user-attachments/assets/041ba6a8-1c5f-4323-8568-b26419011e90" />
