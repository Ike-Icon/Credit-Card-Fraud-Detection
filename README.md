# CREDIT CARD FRAUD DETECTION STORYTELLING
The Goal of this project is to identify patterns that distinguish fraudulent transactions from legitimate ones and present insights with SQL + Power BI dashboard.It also indicat fraudulent behavior and provide actionable insights to reduce financial risk.
## 🔗 Live Links
- [🌐 Portfolio Website](https://ike-icon.github.io/data_analyst_portfolio/)
- [📊 Power BI Dashboard](https://github.com/Ike-Icon/Credit-Card-Fraud-Detection/raw/refs/heads/main/fraud_analysis.pbix)

## KEY FINDINGS
**🔴 Insight 1: Fraud is rare but impactful**
Fraudulent transactions represent a small percentage of total transactions, which is typical in real-world fraud detection. However, despite being rare, they represent significant financial risk.

**💰 Insight 2: Medium-value transactions are riskier**
Fraud is more concentrated in medium and high transaction amounts, indicating that fraudsters tend to target higher-value transactions for maximum gain.
<img src="/fraud_by_trans.png" alt="Logo" width="200"/>

**🌙 Insight 3: Time influences fraud behavior**
Fraud rates vary by time of day, with increased suspicious activity during off-peak hours such as evening periods, suggesting reduced monitoring or opportunistic behavior. 
<img src="/by_time.png" alt="Logo" width="200"/>

**🌍 Insight 4: Foreign transactions are higher risk**
Foreign transactions show a higher proportion of fraud compared to domestic transactions, making them a strong indicator for risk scoring.
<img src="/foreign.png" alt="Logo" width="200"/>

**🚨 Insight 5: Merchant risk score is a strong predictor**
Transactions associated with high-risk merchants exhibit significantly higher fraud rates, indicating that merchant risk scoring is a critical feature in fraud detection.
<img src="/ricks.png" alt="Logo" width="200"/>

## BUSINESS IMPLICATIONS

#### ✅ What should the business DO?
Financial institutions should prioritize monitoring high-value transactions, especially those occurring at night and involving foreign merchants.

Merchant risk scoring should be integrated into real-time fraud detection systems to flag high-risk transactions immediately.

Additional verification steps can be applied selectively to high-risk transactions to reduce fraud without affecting user experience.