📊 Amazon Sales Revenue Risk Analysis (Pandas)

🔍 Project Overview

This project analyzes Amazon sales order data to understand how much revenue is truly realized, at risk, or lost, and where operational focus can recover maximum value.
The analysis is performed using Python (Pandas, NumPy , Matplotlib) with a strong emphasis on decision-oriented analytics rather than surface-level EDA.

🎯 Business Objective

Most sales reports treat shipped orders as revenue, which can overstate business performance.
This project aims to:

- Redefine revenue into meaningful stages

- Identify where revenue risk actually lies

- Narrow large datasets into small, actionable decision sets

🧠 Methodology (High-Level)

- Revenue Funnel Creation

  Orders were categorized into Realized, At Risk, and Lost based on order lifecycle status.

- Value-Based Segmentation

  At-risk orders were bucketed by order value to differentiate volume risk from revenue risk.

- Multi-Dimensional Analysis

  At-risk revenue was further analyzed across:

- B2B vs B2C

- Product categories

- Fulfilment type

- Priority Risk Identification 

  Analysis was narrowed to a small subset of medium/high-value orders representing realistic recovery opportunities.

📊 Key Metrics & Findings

- Revenue Funnel

  At Risk: ~74%

  Realized: ~18%

  Lost: ~8%

- Risk Distribution

  ~88% of at-risk orders are low or very low value

  Medium/high-value risk is highly concentrated

- Recoverable Revenue

  ~22% of total at-risk revenue is realistically recoverable

  This recovery opportunity exists within a small, targeted order segment

📈 Visualization Support

  Key insights were reinforced using focused visualizations such as revenue funnel comparison, distribution of at-risk order values, and category-wise risk contribution. These charts are intentionally minimal and decision-oriented, helping validate analytical findings and highlight where revenue risk is concentrated.


- Operational Insight

  100% of high-priority at-risk revenue is linked to Amazon-fulfilled orders

  Indicates fulfilment-level, not merchant-level, intervention

✅ Key Business Recommendations

- Focus on At-Risk orders rather than only cancellations.

- Apply value-based prioritization to optimize operational effort.

- Prioritize B2C orders, as B2B risk is low value.

- Target the “Set” category, which drives all meaningful at-risk revenue.

- Investigate Amazon fulfilment workflows to improve delivery conversion.

⚠️ Challenges & Limitations

- Single-date data limited time-series analysis

- Missing values required careful handling to avoid revenue distortion

- Maintaining analytical focus while avoiding over-segmentation

🏁 Conclusion

This project demonstrates how Pandas can be used for real business analysis, not just data exploration.
By combining funnel analysis, segmentation, and KPI engineering, the project translates raw sales data into clear, actionable insights suitable for operational and leadership decision-making.