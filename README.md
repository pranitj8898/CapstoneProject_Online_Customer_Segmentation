# CapstoneProject_Online_Customer_Segmentation

**Problem Description**

In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

**Summary**

In this project, the objective is to perform customer segmentation using a transnational dataset that records all the transactions conducted between December 1, 2010, and December 9, 2011, for a UK-based non-store online retail company specializing in the sale of unique all-occasion gifts. This dataset also includes data on a significant number of wholesale customers. The primary aim is to identify distinct customer segments based on their transaction behavior, which can help the company tailor its marketing strategies, improve customer engagement, and optimize its product offerings.

The dataset comprises several key attributes, including Invoice number (unique to each transaction), Product code (StockCode), Product name (Description), Quantity of products purchased in each transaction, Invoice date and time, Unit price of the products, Customer number, and the customer's residing country. The data also accounts for transaction cancellations, marked by an 'c' prefix in the Invoice number. By analyzing these attributes and the customer interactions with the company, the project aims to uncover patterns and differences among customers, potentially leading to more effective marketing campaigns and improved customer experiences, particularly for wholesale and retail customers in different countries.



**Conclusion:**

* Platinum customers=1263 ( less recency but high frequency and heavy spendings)
* Gold customers=1324 (good recency,frequncy and moentary)
* Silver customers=981(high recency, low frequency and low spendings)
* Bronz customers=770 (very high recency but very less frequency and spendings)

We used a technique called K-means clustering to group customers based on three important factors: how recently they made a purchase (recency), how often they make purchases (frequency), and how much money they spend (monetary value). By considering all three factors together, we get a more complete picture of customer behavior.

We found that Cluster 0 includes 2414 customers who haven't made recent purchases and they don't shop frequently or spend much money. In other words, they are less engaged with the retail business.

On the other hand, Cluster 1 includes customers who made purchases more recently, shop frequently, and spend a lot of money. These customers are very valuable to the retail business because they generate a significant amount of revenue.

This analysis helps us understand our customer base better. We can also explore additional methods for clustering, not just based on RFM, but by considering other factors like customer demographics or product preferences. This way, we can create even more effective strategies to serve our customers and grow our business.
