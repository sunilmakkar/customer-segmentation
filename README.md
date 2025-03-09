# **Customer Segmentation Analysis for a UK E-commerce Store**

**Author:** Sunil Makkar, Data Analyst  
**Date of Submission:** March 09, 2025  
**Dataset:** Online Retail II (2009-2011)  

---

## **Executive Summary**

This project conducts a comprehensive customer segmentation analysis for a UK-based online retail company using transactional data from December 2009 to December 2011. The objective is to enable data-driven, customer-centric marketing strategies that maximize profitability and improve customer retention.

Using the Recency, Frequency, and Monetary (RFM) model combined with K-Means clustering, distinct customer segments were identified. Key findings reveal that a small group of high-value customers contributed significantly to overall sales, while a larger portion of low-frequency buyers presented growth opportunities.

**Key Recommendations:**
- Focus marketing efforts on retaining high-value customers by offering exclusive incentives.
- Re-engage inactive customers with targeted promotions.
- Explore personalized campaigns based on purchase behavior to increase loyalty and spending frequency.

---

## **Table of Contents**
1. Introduction
2. Methodology
3. Results
4. Discussion
5. Recommendations
6. Conclusion
7. References

---

## **1. Introduction**

### **Problem Statement**
The company seeks to understand its customer base to drive more effective marketing strategies. Identifying distinct customer segments allows for tailored promotions, enhancing customer retention and profitability.

### **Objectives**
- Segment customers based on purchasing behavior using the RFM model.
- Identify characteristics of high-value and at-risk customer groups.
- Provide actionable recommendations for improving customer engagement and sales.

### **Scope of the Report**
- Transaction data from December 2009 to December 2011.
- Focus on UK-based customer transactions.
- Analysis limited to Recency, Frequency, and Monetary metrics.

---

## **2. Methodology**

### **Data Source**
- **Dataset:** Online Retail II (2009-2011)
- **Variables:** Invoice, StockCode, Description, Quantity, Price, InvoiceDate, CustomerID, Country.

### **Data Cleaning and Preprocessing**
- Removed missing Customer IDs and negative quantities (indicating returns).
- Calculated "Amount" as Quantity x Price.
- Filtered data for UK-based customers.
- Derived RFM metrics per customer.

### **Analytical Methods and Tools**
- **Tools:** Python (pandas, matplotlib, scikit-learn).
- **Clustering Algorithm:** K-Means.
- **Normalization:** Log-transformation and Min-Max scaling.
- **Cluster Evaluation:** Elbow Method to determine optimal cluster count.

### **Assumptions and Limitations**
- Assumes that RFM metrics sufficiently capture customer behavior.
- Limited by historical transaction data and absence of demographic details.

---

## **3. Results**

### **Cluster Overview**
- **Cluster 1 (High Value, Frequent Buyers):** Smallest group but highest spenders, contributing over 25% of total sales.
- **Cluster 2 (Moderate Value, Infrequent Buyers):** Spent less frequently but maintained consistent purchases.
- **Cluster 3 (New and Uncertain Buyers):** Largest group with diverse spending habits.
- **Cluster 4 (Occasional High Spenders):** Less frequent but made large purchases when they did.
- **Cluster 5 (At-Risk, Inactive Buyers):** Least profitable, with low frequency and spending.

### **Key Visualizations**
- Scatter plots of clusters across RFM dimensions.
- Distribution histograms for understanding data skewness.
- Cluster size distribution to highlight potential revenue drivers.

---

## **4. Discussion**

- **High-Value Customers (Cluster 1):** Should be prioritized for loyalty programs and exclusive offers.
- **At-Risk Customers (Cluster 5):** Require re-engagement strategies like personalized promotions to encourage repeat purchases.
- **Uncertain Customers (Cluster 3):** Potential growth segment. More engagement could convert them into loyal buyers.

The analysis suggests that 22% of customers contribute to over 60% of sales, underscoring the importance of targeted marketing strategies to this group.

---

## **5. Recommendations**

1. **Loyalty Programs:** Develop exclusive incentives for top-tier customers (Cluster 1).
2. **Targeted Promotions:** Create campaigns aimed at reactivating dormant customers (Cluster 5).
3. **Behavioral Campaigns:** Use purchase history to personalize product recommendations for medium-tier customers (Clusters 2 and 3).
4. **Monitor Customer Trends:** Regularly analyze transaction data to identify shifts in purchasing behavior.
5. **Geographic Insights:** Further analysis can explore how location influences purchasing patterns.

---

## **6. Conclusion**

This segmentation analysis has successfully identified distinct customer profiles within the dataset, providing a foundation for strategic marketing initiatives. By focusing on high-value customers and re-engaging inactive segments, the business can optimize its marketing efforts, increase customer lifetime value, and drive profitability.

---

## **7. References**
- Chen, D., Sain, S.L., Guo, K. (2012). *Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining*. Journal of Database Marketing & Customer Strategy Management.
- Python Libraries: pandas, matplotlib, scikit-learn.
- Online Retail II Dataset (UCI Machine Learning Repository).

---

**Note:** This report is intended for professional evaluation and strategic decision-making regarding customer segmentation and marketing strategies.

