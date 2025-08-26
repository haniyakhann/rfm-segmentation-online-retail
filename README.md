# 🛍️ RFM Customer Segmentation (Online Retail)

This project applies **RFM analysis (Recency, Frequency, Monetary)** to the **UCI Online Retail dataset** to segment customers based on their purchasing behavior. The workflow includes data cleaning, RFM scoring, customer grouping, and visualizations with actionable insights for marketing strategies.

## Features
- Cleans and preprocesses raw transaction data (removes cancellations, missing IDs, negative values).
- Calculates Recency (days since last purchase), Frequency (number of unique invoices), and Monetary (total spend).
- Assigns quantile-based scores (1–5) for each RFM dimension.
- Builds overall RFM scores and maps customers into segments:
  - Loyal Customers  
  - Potential Loyalists  
  - Need Attention  
  - At Risk  
- Generates visualizations such as segment distribution and average R/F/M heatmaps.
- Exports results to CSV for further analysis.

## Outputs
- `RFM_segments.csv` containing:
  - CustomerID, Recency, Frequency, Monetary, R, F, M, RFM_Score, Segment

## Insights
- **Loyal Customers** are frequent, high spenders who should be rewarded with VIP perks and early access.  
- **Potential Loyalists** are promising customers who can be converted with targeted offers.  
- **Need Attention** customers require engagement campaigns to maintain activity.  
- **At Risk** customers need win-back strategies such as coupons or personalized outreach.  

## Dataset
- **Source:** [UCI Machine Learning Repository – Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)  
- Transactions from a UK-based online retailer (Dec 2010 – Dec 2011).

## License
This project is licensed under the MIT License.
