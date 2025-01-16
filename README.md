# Retail Customer Segmentation

## **Introduction**  
In today’s ever-evolving business landscape, companies leverage technology to expand their reach and cater to diverse customer needs. One powerful strategy for understanding and meeting these needs is **customer segmentation**, which involves grouping customers based on shared characteristics.

This project focuses on identifying major customer segments for a **UK-based online retail business** that primarily sells unique, all-occasion gifts to both individual customers and wholesalers. The dataset spans transactions from **01/12/2009 and 09/12/2011**, offering a rich opportunity to analyze customer behavior and uncover actionable insights. For this analysis, I have only considered 1 year's data i.e., '01/12/2009 - 09/12/2010'.

![Image](https://github.com/user-attachments/assets/5086045f-04bf-4384-b292-3afce15d7630)

---

## **The Need for Customer Segmentation**  
Customers exhibit varying behaviors, preferences, and purchasing patterns. Segmenting customers allows businesses to:  
- **Develop targeted marketing campaigns** that appeal to specific customer groups.  
- Gain **deeper client understanding** to improve engagement and loyalty.  
- **Optimize product placement** to align with customer preferences.  
- **Drive revenue growth** by tailoring services to customer needs.

---

## **Calculating Key Metrics: Monetary Value, Frequency, and Recency**  
To quantify customer value, we calculate three essential metrics:  
- **Recency**: Measures how recently a customer made a purchase.  
- **Frequency**: Captures how often a customer makes purchases.  
- **Monetary Value**: Evaluates how much a customer spends.  

By combining these dimensions, we classify customers. For example, a customer who shops frequently spends significantly and makes recent purchases is considered a **high-value customer**.

---

## **Approach**  
The methodology followed in this project consists of the following steps:  
1. **Data Inspection**: Evaluating the dataset for missing or duplicate values, identifying irrelevant or misaligned data, and cleaning the dataset.  
2. **Exploratory Data Analysis (EDA)**: Analyzing patterns, trends, and customer behaviors to uncover insights.  
3. **Data Preparation**: Structuring and preprocessing the data to ensure consistency and accuracy for further analysis.  
4. **Calculating Key Metrics**: Deriving **Recency, Frequency, and Monetary Value (RFM)** metrics for each customer.  
5. **Clustering Models and Validation**: Applying clustering algorithms such as **KMeans** to segment customers and validate the results to determine the optimal number of clusters.

---

## **Key Findings**  

### **Descriptive Analysis**  
- **Geography**: The majority of purchases originate from the **United Kingdom**.  
- **Purchasing Patterns**: Peak purchasing days are **Thursday, Wednesday, and Tuesday**, with the highest sales recorded during **November, October, and December**.  

### **Clustering Insights** 

![Image](https://github.com/user-attachments/assets/d34b3f98-46b4-44b7-a90a-1376179820ed)

Using the KMeans algorithm, the optimal number of clusters was determined to be four. Each cluster represents a unique customer group with distinct behaviors, and targeted strategies can be developed for each:

- Retain: Customers who frequently shop and have high spending patterns. These are loyal, high-value customers. Strategy: Offer exclusive rewards, personalized services, and loyalty programs to ensure retention.
- Re-Engage: Customers who have decreased activity over time but were previously active. Strategy: Use re-engagement campaigns, discounts, and reminders to bring them back.
- Nurture: New or low-spending customers with growth potential. Strategy: Encourage more frequent purchases through promotions, bundled offers, or targeted content.
- Reward: High-spending customers who purchase infrequently but have significant monetary value. Strategy: Provide incentives such as occasional discounts, premium membership offers, or personalized communication to reward their loyalty.

![Image](https://github.com/user-attachments/assets/7bb5e149-bca9-426e-b498-43898445e452)

---

## **Conclusion**  
This project highlights the value of customer segmentation by clustering them into different clusters based on their behavior. By segmenting customers into meaningful groups, businesses can implement targeted marketing strategies, enhance customer satisfaction, and drive business growth. Focusing on the unique needs of each customer cluster provides a pathway for more personalized services and improved operational efficiency, resulting in a significant competitive advantage.
