# Beyond the 'Buy' Button  
### An Operations and Marketing Analysis of Olist - Brazil’s leading ecommerce player  

**Study Group: Group 8**  
**Course: AM 10 Final Group Project - Poster Proposal**  
**Date: 3rd November 2025**

---

## OVERVIEW  

This project conducts a comprehensive **operational and marketing analysis** of a two-sided e-commerce marketplace. We would conduct this analysis using a Brazilian online marketplace's database of items, transactions, customers, sellers, etc. The primary goal is to move beyond simple sales metrics and identify the core strategic levers that drive **customer satisfaction, retention, and platform health**.  

The analysis addresses three key business questions:

- **Operational Excellence:**  
  What are the key operational drivers of customer satisfaction?
  What drives negative reviews?
  Specifically, how much does **logistics performance** (e.g., delivery time vs. estimated time) impact customer review scores compared to factors like **price** or **product category**?

- **Customer-Centric Marketing:**  
  How can we segment the customer base into actionable cohorts?
  Who are our most valuable customers (both buy and sell side?)
  The goal is to identify **high-value**, **loyal**, and **"at-risk"** customers to inform targeted marketing strategies and reduce churn.

- **Platform Strategy:**  
  What **geographic** and **product-level** patterns reveal strengths or weaknesses?  
  Where are the logistical points of failure, and which product categories are associated with the highest (and lowest) customer satisfaction?

---

## GOALS  

1. To synthesize **9 raw, separate files** into a single and clean **"analytical dataset."**  
2. To translate the raw data into interpretable **business metrics (features)** and formulate the specific questions our analysis will answer.  
3. To use **statistical and machine learning techniques** to test our hypotheses and generate predictive insights.  
4. To synthesize our findings into a clear, compelling **visual narrative**.

---

## Data Extraction & Cleaning  

The data for this analysis is the **[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**. :contentReference[oaicite:0]{index=0}  
This is an anonymized dataset capturing **100,000 orders** from **2016 to 2018**.  

Its primary complexity lies in its relational structure: the data is spread across **nine separate CSV files** (covering orders, payments, reviews, customers, sellers, and products).  
The initial data processing, therefore, involves a significant **data engineering step** to correctly merge and clean these disparate tables into a single, unified analytical file.

To answer our key questions, we will employ a mix of **statistical** and **machine learning** techniques:

- Use **Multiple Linear Regression** to quantify the precise impact of variables like `delivery_delay` and `freight_value` on the `review_score`.  
- For customer segmentation, engineer features using **RFM (Recency, Frequency, Monetary)** analysis and apply **K-Means Clustering** to discover natural customer groupings.  
- Finally, use **Geospatial Analysis (GeoPandas)** to map seller/customer locations and operational delays, providing a visualization of the platform’s logistical performance across Brazil.
