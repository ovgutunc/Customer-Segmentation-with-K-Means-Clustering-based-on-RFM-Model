# Customer-Segmentation-with-K-Means-Clustering-based-on-RFM-Model

## **Introduction:**
This project aims to divide customers into segments based on RFM method and K-Means Clustering Model, which in turn creates tailored marketing strategies according to the customer behavior, characteristics, and needs.<br>
Here’s the overview of the workflow followed in this project:

•	Define the business task and methods, which is K-Means Clustering algorithm with measurement metrics(RFM values) to solve the problem<br>

•	Conduct a comprehensive analysis, including data understanding, pre-processing, and exploratory data analysis (EDA)<br>

•	Perform feature engineering, including feature creation for RFM model<br>

•	Divide the customer into segments based on RFM values<br>

•	Transform the dataset by log transform and normalization before fitting K-Means Clustering model<br>

•	Determine the optimum number of clusters by comparing the results of Elbow and Silhoutte method<br>

•	Fit the model on the final dataset and find the K-Means Clusters<br>

•	Explore and compare distributions of RFM groups and K-Means Clusters based on RFM values<br>

•	Discuss the results and make recommendations for the clusters<br>

To get detailed information about customer segmentation with K-means clustering, please check out Jupyter Notebook.<br>

## **Data Understanding:**

The dataset contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. It can be found here and the attributes are as follows.<br>

**InvoiceNo:** Invoice number, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.<br>

**StockCode:** Product (item) code, 5-digit integral number uniquely assigned to each distinct product.<br>

**Description:** Product (item) name <br>

**Quantity:** The quantities of each product (item) per transaction.<br>

**InvoiceDate:** Invice Date and time,the day and time when each transaction was generated.<br>

**UnitPrice:** Unit price, Product price per unit in sterling.<br>

**CustomerID:** Customer number, a 5-digit integral number uniquely assigned to each customer.<br>

**Country:** Country name, the name of the country where each customer resides.<br>

The link to the datasets is here.<br>

## **Results:**

<p align="center">

<img src="https://github.com/ovgutunc/Customer-Segmentation-with-K-Means-Clustering-based-on-RFM-Model/blob/main/images/3d_scatter.PNG" alt="cluster" width="600" height="600">

• Cluster 2 is the high value customers with the highest number of orders, frequency and the most recent transactions.<br>

• Cluster 1 is the lost customers who rarely place orders with the lowest amount of sales.<br>

• Cluster 0 encompasses at risk and loyal customers with medium value of frquency, recency and monetary.<br>

• High monetary value is correlated with high frequency of orders and more recent ones in all clusters.<br>

• The company can create different marketing campaigns for the customer segments to grow revenue based on online retailer policies. In that sense, the company can offer incentives to low-value customers to keep them engaged and increase their frequency of orders. On the other hand, they can offer privileges such as exclusive discounts and early access to new products. Overall, it depends on what the company's business goal is.<br>
