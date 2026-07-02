# Financial Risk Analysis Using Python

## Project Overview
This project analyzes financial transaction data to identify transaction trends, customer activity patterns, account performance, and potential financial risks.

The analysis was performed on 800 transaction records using Python in Google Colab.

## Objectives
- Clean and prepare financial transaction data
- Analyze transaction patterns by month, transaction type, and account type
- Segment customers based on transaction activity and account balance
- Identify large withdrawals, transaction anomalies, and suspicious customers
- Perform statistical hypothesis testing on Deposit and Withdrawal transactions
- Generate visualizations and business insights

## Key Findings
- The dataset contains 800 records and 15 columns.
- No missing values or duplicate records were found.
- Loan accounts recorded the highest transaction volume at approximately ₹11.24 million.
- Medium Activity customers formed the largest segment with 109 customers.
- The highest monthly transaction volume was recorded in September 2023 at approximately ₹3.18 million.
- 21 large withdrawals were identified.
- 1 transaction anomaly and 1 suspicious customer, CUST3015, were identified.
- ACC21878 had the highest balance volatility at approximately ₹70,517.53.
- The hypothesis test found no statistically significant difference between average Deposit and Withdrawal transaction amounts (p-value: 0.9198).

## Tools Used
- Python
- Google Colab
- Pandas
- Matplotlib
- SciPy

## Project Structure
```text
financial-risk-analysis-python/
│
├── Financial_Risk_Analysis.ipynb
├── goldman_sachs.csv
└── README.md
