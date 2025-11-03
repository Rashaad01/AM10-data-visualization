# 🛍️ Beyond the "Buy" Button  
### An Operations and Marketing Analysis of **Olist** — Brazil’s Leading E-Commerce Player  

**Course:** AM10 Final Group Project  
**Group:** 8  
**Date:** November 3, 2025  

---

## 📖 Overview  

This project conducts a comprehensive **operational and marketing analysis** of a two-sided e-commerce marketplace.  
The goal is to move beyond simple sales metrics and uncover the **core strategic levers** that drive:

- Customer satisfaction  
- Retention  
- Platform health  

The analysis addresses three key business questions:

### 1️⃣ Operational Excellence  
What are the key operational drivers of customer satisfaction?  
Specifically, how much does **logistics performance** (e.g., delivery time vs. estimated time) impact customer review scores compared to factors like **price** or **product category**?

### 2️⃣ Customer-Centric Marketing  
How can we segment the customer base into **actionable cohorts**?  
The goal is to identify **high-value**, **loyal**, and **at-risk** customers to inform targeted marketing strategies and reduce churn.

### 3️⃣ Platform Strategy  
What **geographic** and **product-level** patterns reveal strengths or weaknesses?  
Where are the logistical “hotspots” of failure, and which product categories are linked to the highest (and lowest) customer satisfaction?

### 💬 Capturing the "Voice of the Customer"  
To add a creative and qualitative layer, we will analyze the most common phrases in **1-star reviews** and generate a  
**“Word Cloud of Rage”** to visually support our quantitative findings.

---

## 🎯 Goals  

1. **Data Integration:** Combine 9 raw, separate files into a single, clean “master analytical dataset.”  
2. **Feature Engineering:** Translate raw data into business metrics (features) and frame specific analytical questions.  
3. **Modeling:** Use statistical and ML techniques to test hypotheses and generate predictive insights.  
4. **Visualization:** Synthesize findings into a clear, compelling visual narrative in the form of a **poster presentation**.

---

## 🧹 Data Extraction & Cleaning  

The data for this analysis comes from the  
**[Brazilian E-Commerce Public Dataset by Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)** —  
a real-world, anonymized dataset capturing ~100,000 orders from **2016–2018**.

### Key Characteristics
- Data is **relational**, spread across **nine CSV files** (orders, payments, reviews, customers, sellers, and products).  
- Initial steps involve significant **data engineering** to merge and clean these tables into a single analytical dataset.

---

## 🧠 Analytical Approach  

To answer our business questions, we’ll employ a mix of **statistical** and **machine learning** techniques:

### 📊 Regression Analysis  
Use **Multiple Linear Regression** to measure the impact of:
- `delivery_delay`  
- `freight_value`  
on **review_score**.

### 👥 Customer Segmentation  
- Conduct **RFM (Recency, Frequency, Monetary)** analysis to engineer customer-level features.  
- Apply **K-Means Clustering** to uncover natural customer segments.

### 🗺️ Geospatial Analysis  
Using **GeoPandas**, we’ll map:
- Seller and customer locations  
- Delivery performance and delay patterns across Brazil  

This geospatial visualization will highlight operational strengths and weaknesses across regions.

---

## 📈 Expected Outcomes  

- Unified analytical dataset for Olist operations and marketing.  
- Quantitative insights into logistics performance vs. satisfaction.  
- Actionable customer segments for marketing optimization.  
- Visual “Word Cloud of Rage” capturing key customer pain points.  
- Poster summarizing findings for presentation.

---

## 🧰 Tools & Technologies  

| Category | Tools / Libraries |
|-----------|------------------|
| **Data Wrangling** | pandas, numpy |
| **Statistical Modeling** | statsmodels, scikit-learn |
| **Clustering & ML** | K-Means, RFM analysis |
| **Visualization** | matplotlib, seaborn, plotly |
| **Geospatial Analysis** | geopandas |
| **Source Data** | Olist Dataset (Kaggle) |

---

## 👩‍💻 Team  

**Group 8**  
AM10 Final Project – Poster Proposal  

📅 *3rd November 2025*

---
