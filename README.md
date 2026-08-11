# UPI-Transaction-Analytics-Dashboard (Interactive Dashboard using Power BI)
Developed a Power BI dashboard to analyze 250K+ UPI transactions, uncovering transaction trends, payment patterns, and performance insights using Power Query and DAX.
## Project Objective
To analyse UPI transaction data using Power BI to identify transaction trends, payment patterns, and key performance indicators for data-driven insights.

## Dataset used
- <a href="https://www.kaggle.com/datasets/skullagos5246/upi-transactions-2024-dataset">Dataset</a>

## Questions 
- How many UPI transactions were processed?
- What is the total transaction value?
- What is the average transaction value?
- How has transaction activity changed over time?
- Which months have the highest transaction activity?
- What is the split between P2P and P2M transactions?
- Which banks process the highest transaction value?
- Which states contribute the most transaction value?
- What is the transaction success rate?
- Which merchant categories have the highest transaction value?
- What are the peak hours for UPI transactions?

## Dashboard Interaction
- <a href="https://github.com/riyak11/UPI-Transaction-Analytics-Dashboard-/blob/main/Dashboard.png">View Dashboard</a>

## Process
- Imported the 250K+ UPI transaction dataset into Power BI. 
- Cleaned and transformed the data using Power Query, including handling data types and creating date and time-slot fields. 
- Created calculated columns for Time Slot and Day Type to support transaction analysis. 
- Developed DAX measures to calculate key KPIs including Total Transactions, Transaction Value, Average Transaction Value, Success Rate & Failure Rate. 
- Built interactive visuals to analyse monthly trends, bank and state-wise performance, transaction types, merchant categories, and transaction time slots. 
- Added slicers for category, month/year, state, bank, and transaction type for dynamic filtering. 
- Designed a one-page interactive dashboard with KPI cards, charts, slicers, and consistent formatting. 
- Analysed the dashboard to identify transaction patterns, performance trends, and areas of potential improvement.
## Dashboard
<img  />

## Insights 
- SBI is the leading bank, accounting for 34.8% of the total transaction value among the top 5 banks.
- Maharashtra recorded the highest transaction value at ₹49M, followed by Uttar Pradesh at ₹40M.
- Shopping is the top merchant category with ₹77M in transaction value, making it the largest spending segment.
- 26-35 age group contributes the highest transaction value at ₹116M, indicating stronger UPI activity among young adults.
- P2P transactions dominate payment activity at 44.98%, followed by P2M at 35.06%.
- 95.05% of transactions were successful, while 4.95% failed, indicating a high overall transaction success rate.
- May recorded the highest monthly transaction volume at approximately 21.3K, while February had the lowest at 19.8K.

## Final Conclusion
The UPI ecosystem processed 250K+ transactions worth ₹328M, driven by strong activity from SBI, Maharashtra, the 26-35 age group, and the Shopping category, with P2P transactions dominating payment activity. However, the 4.95% failure rate indicates an opportunity to improve transaction reliability. Improving transaction success rates and focusing on high-performing banks, regions, and merchant categories can enhance payment efficiency and support sustainable growth.
