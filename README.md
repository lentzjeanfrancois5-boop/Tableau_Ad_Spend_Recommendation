## 💡 Executive Summary

A comprehensive data-driven analysis using Tableau to recommend optimal advertising investment. This project identified three high-profit State-Month combinations. However, a crucial cross-reference with the **Avg Profit vs Avg Return Rate** metric revealed that all three areas reside in a **high-risk segment** (high return rate, low efficiency).

Therefore, the final recommendation is to **hold the calculated ad budget of **$2,209.80**** and first stabilize the high return rates before campaign deployment.

# 🔹 Dashboard Preview  
![Final Project Dashboard Screenshot](./FirstScreenshot.png)

🔗 **Live Dashboard (Tableau Public)** → [View Here](https://public.tableau.com/app/profile/lentz.francois/viz/Ad_Spend_Analysis_DashboardLentzJeanFrancois/OverallProjectSummary?publish=yes)

## 📈 Project Assets and Visualizations

* **[See Full Tableau WorkBook](https://public.tableau.com/app/profile/lentz.francois/viz/Ad_Spend_Analysis_DashboardLentzJeanFrancois/OverallProjectSummary?publish=yes)**: View all underlying sheets and data, including Profit & Loss, Customer Return Rates, and Product Return Rates.
* **[View Critical Risk Scatter Plot (Screenshot)](https://public.tableau.com/app/profile/lentz.francois/viz/Ad_Spend_Analysis_DashboardLentzJeanFrancois/AVGProfitvs_AvgReturnRate?publish=yes)**: See the visualization that revealed the high-risk nature of the three identified combinations.

## 💰 Top 3 Identified Combinations & Potential Budget

The following combinations were identified as having the highest total profit, but this profit is deemed **unstable** due to associated risk factors.

| Rank | State-Month Combination | Total Profit (SUM(Profit)) | Recommended Ad Spend (20% of Profit) |
| :--- | :--- | :--- | :--- |
| **#1** | **Indiana - October** | $9,004 | **$1,800.80** |
| **#2** | **Vermont - November** | $1,192 | **$238.40** |
| **#3** | **Minnesota - October** | $853 | **$170.60** |
| | **TOTAL IDENTIFIED SPEND** | **$11,049** | **$2,209.80** |

## 🔍 Supporting Analysis: Risk & Contradiction

The analysis shifted from an initial recommendation to a **critical risk assessment** based on the following findings:

1.  **High Risk Investment (Contradiction):** The **Avg Profit vs Avg Return Rate** scatter plot shows that all three combinations are situated in the highest return rate range ($0.2 - 0.4$), indicating a volatile and risky investment area.
2.  **Customer Reliability:** The products are being sold to a generally reliable customer base (e.g., Aaron Bergman, Aaron Hawkins, and Aaron Smayling associated with the lowest return rates). This suggests the issue is likely rooted in the **fulfillment or quality control process** specific to these states and months.
3.  **Product Quality:** Low return rates were confirmed for commodity items (Envelopes). The high return rate in the target areas suggests that other, less stable products are driving the sales volume.

## Conclusion and Next Steps

Based on the conflicting data—high SUM(Profit) versus high return risk—it is recommended that the **$2,209.80** ad budget be temporarily **held**. The company should first execute a deep dive into the **fulfillment and quality control issues** specific to Indiana in October, Vermont in November, and Minnesota in October to mitigate the risk. Only after the high return risk is addressed should the targeted advertising campaigns be launched.
