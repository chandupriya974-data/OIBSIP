**OIBSIP Customer Segmentation Analysis**





**Project Overview**



This project focuses on customer segmentation for an e-commerce business using

&#x20;RFM (Recency, Frequency, and Monetary) analysis and K-Means clustering.



The objective is to identify distinct customer groups based on purchasing

&#x20;behaviour and provide actionable marketing strategies for each segment.



**Dataset**



**Dataset**: Online Retail Dataset



The dataset contains transactional information including:



\- Invoice Number

\- Stock Code

\- Product Description

\- Quantity

\- Invoice Date

\- Unit Price

\- Customer ID

\- Country



**Technologies Used**



\- Python

\- Pandas

\- NumPy

\- Scikit-learn

\- Matplotlib

\- Seaborn

\- Jupyter Notebook



**Data Preparation**



The dataset was inspected and cleaned by:



\- Handling missing Customer IDs

\- Removing duplicate records

\- Calculating Total Amount using Quantity × Unit Price

\- Creating a snapshot date for RFM analysis



**RFM Analysis**



Three customer behaviour features were created:



**- Recency:** Number of days since the customer's most recent purchase

**- Frequency:** Number of unique invoices/orders made by the customer

**- Monetary:** Total amount spent by the customer



The RFM features were standardized using "StandardScaler" before clustering.



**Customer Segmentation**



K-Means clustering was applied to the standardized RFM data.



The Elbow Method was used to determine a suitable number of clusters. Based on the analysis, 5 customer clusters were selected.



The identified segments are:



1\. Regular Customers

2\. At-Risk / Lost Customers

3\. High-Value Customers

4\. Champions / VIP Customers

5\. Loyal Customers



**Visualizations**



The project includes:



\- Elbow Method chart

\- Number of customers per cluster

\- Recency vs Monetary scatter plot

\- Frequency vs Monetary scatter plot

\- Customer Segment Distribution chart



**Customer Insights**



**Regular Customers**



These customers purchase occasionally and have moderate purchasing activity.



**Marketing Action:** Use personalized offers, product recommendations, and loyalty

&#x20;incentives to increase purchase frequency.



**At-Risk / Lost Customers**



These customers have not purchased recently and have relatively low

&#x20;purchase frequency and spending.



Marketing Action: Use re-engagement campaigns, special discounts, and limited-time 

offers to encourage them to return.



**High-Value Customers**



These customers are recently active and generate extremely high spending.



**Marketing Action:** Provide premium offers, personalized recommendations,

&#x20;early access to new products, and VIP benefits.



**Champions / VIP Customers**



These customers purchase very frequently and generate high 

revenue while remaining recently active.



**Marketing Action:** Reward them with exclusive loyalty benefits,

&#x20;referral programs, VIP support, and early access to products.



**Loyal Customers**



These customers purchase frequently and generate good revenue while remaining recently active.



**Marketing Action:** Strengthen loyalty through membership rewards,

&#x20;personalized promotions, and cross-selling opportunities.



**Conclusion**



The customer segmentation analysis successfully grouped customers based on their

&#x20;purchasing behaviour using RFM analysis and K-Means clustering.



The resulting customer segments help the business understand customer value, 

identify customers who may need re-engagement, and recognize high-value and loyal customers.



These insights can support targeted marketing campaigns, customer retention strategies,

&#x20;personalized promotions, and improved business decision-making.

