# Beyond the 'Buy' Button  
### An Operations and Marketing Analysis of Olist - Brazil’s leading ecommerce player  

**Study Group:** Group 8
**Course:** AM10 Final Group Project - Poster Presentation  
**Date:** 16th November 2025

---

## REPOSITORY INFORMATION
This repository contains an analysis of the transaction information for 100,000 orders of an e-commerce platform, Olist. It employs key analytical tools such as **...**, and presents thought-provoking insights for boosting revenue. It synthesizes nine raw files into a single analytical dataset and employs SQL through DBeaver, Python, and visualization techniques to uncover insights for boosting revenue.

## BACKGROUND 

Every business venture is incentivized to scale in pursuit of its broader strategic objectives. For Olist, a Brazilian e-commerce marketplace dedicated to making products accessible to consumers, this is no different. As a young company, Olist aimed to connect small businesses with customers while managing all operational logistics and delivery requirements. After experiencing exponential growth in its early years, the CEO engaged our team to answer a core question:

**What strategies can help Olist triple its revenue in two years?**

## PROJECT OBJECTIVES
We aligned with the CEO to explore the following:

1) What has been Olist's business performance over the past 3 years?
2) What drives negative customer experiences? Are these experiences uniform across all customer geographies?
3) How often are repeat purchases across top product categories?
4) What are the key drivers of customer loyalty and how does product categorization incentivise it?
   
## DATA AND METHODOLOGY

- The database includes information on **orders, products, order payments, order items, sellers, customers, reviews, and geographies.**
- Our inspection, cleaning, and exploration processes involved handling missing values, validating data types, reviewing product classifications, and analyzing outliers to improve the reliability of the dataset.
- The analysis included an in-depth review assessment using a **word cloud** and a **proportional breakdown** of delivery-related vs. product-related complaints. **Bar charts** and a **bubble chart** were also used to examine customer repeat-purchase behavior across top product categories, preferred payment methods, and installment options.
- A root cause analysis of logistical challenges was performed by combining insights from customer geographies and review patterns. Finally, a **cluster analysis** was conducted to better understand customer repeat-purchase behavior.

**Data Source:** The data for this analysis is the **[Brazilian E-Commerce Public Dataset by Olist (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**.

## PROJECT FILES
- The python file entailing all codes is found here: 

## KEY FINDINGS AND RECOMMENDATIONS

1) Logistics problem, and not product quality is the primary driver of negative customer experiences​. However, this problem is not uniform across all cities. 

2) Repeat purchases are extremely rare on Olist - but the few repeat customers come from home appliances, furniture and bedroom necessities.

3) Customer loyalty varies sharply by payment behaviour, obscuring the true drivers of repeat purchases. Customers with vouchers were most incentivised to repeat purchases. 

4) We recognized that Olist has a highly inconsistent category system which hinders product performance across all categories.

We made key recommendations across the three key areas:

1) Service Delivery and Customer Satisfaction: Olist must focus on tailored delivery services for Rio de Janeiro and other low delivery performance areas. Given the instrumentality of health & beauty products in driving revenue, Olist must provide a priority delivery service for that category.
   
2) Customer Purchase Behavior: Olist must invest in categories with high repeat purchase rate but low penetration while encouraging vouchers and cross-category recommendations to incentivise repeat purchases.​

3) Plaform Ease of Use: Olist must re-create a more intuitive category hierarchy to ease navigation.​ Additionally, delivery and product
reviews to improve clarity on true product quality.

## FOR FULL ANALYSIS
```bash
git clone https://github.com/Rashaad01/AM10-data-visualization.git
cd AM10-data-visualization
jupyter notebook


