# Beyond the 'Buy' Button  
### An Operations and Marketing Analysis of Olist - Brazil’s leading ecommerce player  

**Study Group: Group 8**  
**Course: AM10 Final Group Project - Poster Presentation**  
**Date: 16th November 2025**

---

## BACKGROUND 

Every business venture is incentivized to scale in pursuit of its broader strategic objectives. For Olist, a Brazilian e-commerce marketplace dedicated to making products accessible to consumers, this is no different. As a young company, Olist aimed to connect small businesses with customers while managing all operational logistics and delivery requirements. After experiencing exponential growth in its early years, the CEO engaged our team to answer a core question:

**What strategies can help Olist triple its revenue in two years?**

## PROJECT OBJECTIVES
In a meeting with the CEO, the following project objectives were defined:

1. Synthesize **9 raw, separate files** into a single and clean **"analytical dataset."**  
2. Translate the raw data into interpretable **business metrics (features)** and address key questions on service quality & customer satisfaction, customer purchase behaviour and the ease of use of the Olist platform.
3. Conduct in-depth analysis of the data to produce a compelling **visual narrative** on Olist's performance over the past 3 years, and define recommendations for revenue growth.
4.  Use **Geospatial Analysis (GeoPandas)** to map seller/customer locations and operational delays, providing a visualization of the platform’s logistical performance across Brazil.
   
## DATA AND METHODOLOGY
1) We received raw CSV files containing data on 100,000 orders, including information on products, order payments and items, sellers, and customers. To enable a comprehensive analysis, we imported these files into a database using DBeaver. Our inspection, cleaning, and exploration processes involved handling missing values, ensuring appropriate data types, examining product classifications within the dataset, and analyzing outliers to enhance the reliability of our results.
   
2) During our data exploration, we discovered that order volumes had stagnated, accompanied by an increase in negative customer reviews. This prompted a deeper analysis of all reviews, using a **word cloud** and a **proportional review assessment** (delivery-related vs. product-related reviews). We also employed **bar charts** and a **bubble chat** to examine customer repeat-purchase behavior, focusing on top product categories, preferred payment methods, and installment options.

3) Finally, we skewed down to a root cause analysis of logistical problems by considering them in light of all customer geographies and reviews. A **cluster analysis** was conducted to understand customer repeat purchasing habits.
   
## KEY FINDINGS
​1) Logistics problem, and not product quality is the primary driver of negative customer experiences​. However, this problem is not uniform across all cities. Hence, we can ensure a targeted, regional intervention in high-priority cities​
2) Repeat purchases are extremely rare on Olist - but the few repeat customers come from home appliances, furniture and bedroom necessities.


## CONCLUSION


