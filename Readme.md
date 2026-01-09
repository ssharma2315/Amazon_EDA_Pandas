# Amazon Sales Analysis – Revenue & Fulfilment Insights

## 📌 Overview
This project analyzes Amazon sales data to understand how revenue is realized, where it is at risk, and how fulfilment methods impact successful order delivery.  
The focus is on **business-oriented revenue classification** rather than raw aggregation.

---

## 🎯 Objectives
- Clean and prepare raw sales data
- Classify revenue into meaningful business buckets
- Identify fulfilment-related risks
- Provide actionable recommendations

---

## 🛠️ Tools Used
- Python (Pandas, NumPy)
- Google Colab
- Git & GitHub

---

## 💰 Revenue Segmentation
Revenue was classified into three buckets based on order status:

- **Realized** → Delivered orders  
- **At Risk** → Shipped but not delivered  
- **Lost** → Cancelled / Returned / Rejected orders  

This avoids overstating revenue and improves decision-making accuracy.

---

## 📊 Key Insights
- Majority of orders fall under **At Risk** revenue
- **Easy Ship (Merchant fulfilment)** accounts for **100% of realized revenue**
- Easy Ship represents ~22% of orders but has the highest delivery success rate

---


## ✅ Recommendations

- Focus on At-Risk orders: ~74% of orders are shipped but not delivered, making conversion improvement the highest revenue lever.

- Use value-based prioritization: ~88% of at-risk orders are low value and can be handled via automation, while medium/high-value orders need manual attention.

- Prioritize B2C over B2B risk: All B2B at-risk orders are very low value; revenue risk is driven mainly by B2C orders.

- Target the “Set” category: Medium and high-value at-risk orders are concentrated in this category, enabling focused intervention.

- Segment revenue reporting: Separate Realized, At-Risk, and Lost revenue to avoid overstating performance.


---

## 📌 Conclusion
This analysis demonstrates how aligning data analysis with business logic leads to more reliable insights and better operational decisions.

---

## 👤 Author
**Saransh Sharma**  

