# Beyond the 'Buy' Button  
### An Operations and Marketing Analysis of Olist - Brazil’s leading ecommerce player  

**Study Group: Group 8**  
**Course: AM10 Final Group Project - Poster Presentation**  
**Date: 16th November 2025**

---

## REPOSITORY INFORMATION
This repository contains an analysis of the transaction information for 100,000 orders of an e-commerce platform, Olist. It employs key analytical tools such as **...**, and presents thought-provoking insights for boosting revenue. This analysis was performed by synthesizing **9 raw, separate files** into a single and clean **"analytical dataset."**

## BACKGROUND 

Every business venture is incentivized to scale in pursuit of its broader strategic objectives. For Olist, a Brazilian e-commerce marketplace dedicated to making products accessible to consumers, this is no different. As a young company, Olist aimed to connect small businesses with customers while managing all operational logistics and delivery requirements. After experiencing exponential growth in its early years, the CEO engaged our team to answer a core question:

**What strategies can help Olist triple its revenue in two years?**

## PROJECT OBJECTIVES
In a meeting with the CEO, we aligned to explore the following questions:

1) What has been Olist's business performance over the past 3 years?
2) What drives negative customer experiences? Are these experiences uniform across all customer geographies?
3) How often are repeat purchases across top product categories?
4) What are the key drivers of customer loyalty and how does product categorization incentivise it?
   
## DATA AND METHODOLOGY

1) We received raw CSV files containing data on 100,000 orders, including information on products, order payments and items, sellers, and customers. To enable a comprehensive analysis, we imported these files into a database using DBeaver. Our inspection, cleaning, and exploration processes involved handling missing values, ensuring appropriate data types, examining product classifications within the dataset, and analyzing outliers to enhance the reliability of our results.
   
2) During our data exploration, we discovered that order volumes had stagnated, accompanied by an increase in negative customer reviews. This prompted a deeper analysis of all reviews, using a **word cloud** and a **proportional review assessment** (delivery-related vs. product-related reviews). We also employed **bar charts** and a **bubble chat** to examine customer repeat-purchase behavior, focusing on top product categories, preferred payment methods, and installment options.
   
3) Finally, we skewed down to a root cause analysis of logistical problems by considering them in light of all customer geographies and reviews. A **cluster analysis** was conducted to understand customer repeat purchasing habits.

*Data Source:* The data for this analysis is the **[Brazilian E-Commerce Public Dataset by Olist (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)**.

## PROJECT FILES

## KEY FINDINGS

1) Logistics problem, and not product quality is the primary driver of negative customer experiences​. However, this problem is not uniform across all cities. Hence, we can ensure a targeted, regional intervention in high-priority cities​.

2) Repeat purchases are extremely rare on Olist - but the few repeat customers come from home appliances, furniture and bedroom necessities.

3) Customer loyalty varies sharply by payment behaviour, obscuring the true drivers of repeat purchases. Customers with vouchers were incentivised to repeat purchases as compared to custmers with other payment methods.

4) We recognized that Olist has an highly inconsistent category system which hinders product performance across all categories.

## RECOMMENDATIONS
We made key recommendations across the three key areas:

1) Service Delivery and Customer Satisfaction: Olist must focus on tailored delivery services for Rio de Janeiro and other low delivery performance areas. Given the instrumentality of health & beauty products in driving revenue, Olist must provide a priority delivery service for that cateogry.
   
2) Customer Purchase Behavior: Olist must invest in categories with high repeat purchase rate but low penetration while encouraging vouchers and cross-category recommendations to incentivise repeat purchases.​

3) Plaform Ease of Use: Olist must re-create a more intuitive category hierarchy to ease navigation.​ Additionally, delivery and product
reviews to improve clarity on true product quality.

## FOR FULL ANALYSIS
```bash
git clone https://github.com/Rashaad01/AM10-data-visualization.git
cd AM10-data-visualization
jupyter notebook
'''

