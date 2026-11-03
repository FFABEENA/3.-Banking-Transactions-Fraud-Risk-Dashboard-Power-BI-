# Banking Transactions & Fraud Risk Dashboard (Power BI)

A 3-page interactive Power BI report on digital banking transactions, built to monitor transaction performance, detect fraud patterns and understand customer banking behaviour.

## Dataset
- **Size:** 12,000 banking transactions
- Fields include transaction type, amount, payment mode, status, city, account type, device, platform, category and fraud flag

## Dashboard pages
1. **Transaction Overview & Performance** – total transactions, total amount, average transaction value, success rate, daily trend, credit vs debit, payment modes, categories, city map
2. **Fraud Detection & Risk Analysis** – fraud transactions, fraud rate, fraud by platform, device and transaction type, fraud map, fraud status matrix
3. **Customer & Banking Insights** – unique customers, account types, device vs platform usage, payment modes, top customers

## What I did
- Cleaned and transformed data in **Power Query** and built a city–state lookup table with relationships
- Wrote **DAX measures**: Total Transactions, Total Amount, Average Transaction Value, Successful / Failed Transactions, Success Rate %, Fraud Transactions, Fraud Rate %, Total Credit / Debit Amount, Unique Customers
- Added slicers for platform, category, device, city and transaction type

## Key insights
- NetBanking is the most used payment mode; credit and debit transactions are nearly balanced
- Recharge and Shopping categories drive the largest share of transactions
- Mobile devices dominate digital banking activity, and savings accounts contribute most of the volume
- Android records more failed transactions; Android and Chrome platforms show higher fraudulent activity

## Files
| File | Description |
|------|-------------|
| `Banking_Fraud_Risk_Dashboard.pbix` | Power BI report (open in Power BI Desktop) |
| `Dataset_Banking_Transactions.xlsx` | Source dataset |

## Tools
Power BI · Power Query · DAX · Data Modelling

---
*Fabeena Fasal* · [LinkedIn](https://www.linkedin.com/in/fabeena-fasal)
