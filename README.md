# Customer-Segmentation-with-K-Means-Clustering-based-on-RFM-Model

## **Introduction:**
This project aims to divide customers into segments based on RFM method and K-Means Clustering Model, which in turn creates tailored marketing strategies according to the customer behavior, characteristics, and needs.<br>

[Check out the detailed report and source code]()

## **Data Understanding:**

The dataset obtained from [UCI Machine Learning Dataset repository](http://archive.ics.uci.edu/ml/datasets/online+retail), contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The attributes include invoice number, product code, product name, quantity per transaction, invoice date, product unit price, customerID, and country. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## **Recency-Frequency-Monetary (RFM) analysis to determine customer value:**

RFM (Recency, Frequency, Monetary) Analysis is a customer segmentation technique for analyzing customer value based on past buying behavior. RFM stands for the three values:

• **Recency :** The time since last order with the product of customers.<br>
• **Frequency :** The total number of transaction between the customer’s invoice date and reference day.<br>
• **Monetary :** The total transaction value of customers.<br>

After applying data pre-processing, exploratory data analysis, and feature engineering, a customer's value to a business can be quantified by considering a combination of R,F,M values. For example, a customer who has made recent high-value purchases and frequently engages in transactions is considered as high value to the business.<br>

## **Customer Segmentaton with K-Means Clustering on RFM values:**

K-Means clustering is one of the distance-based and unsupervised machine learning algorithms. It partitions the data points into k clusters based on the Euclidean Distance used for the clustering. It is sensitive to skewness and outliers, which can cause the clusters to be distorted and lead to inaccuracies in the results. In this manner, log transform can be used to turn a skewed distribution into a normal or less-skewed. Following this, normalization is required to prevent one attribute outweighs another one in terms of the scales. Finally, before applying the K-Means Clustering algorithm, the optimum number of k should be defined. The two ways of defining the number of clusters in this dataset are as follows:<br>

• Elbow Method<br>
• Silhouette Method<br>

Afterward, the model can fit into the final dataset and end up with K-means clusters.<br>

## **Results:**

<p align="center">

<img src="https://github.com/ovgutunc/Customer-Segmentation-with-K-Means-Clustering-based-on-RFM-Model/blob/main/images/3d_scatter.PNG" alt="cluster" width="600" height="600">

• Cluster 2 is the high value customers with the highest number of orders, frequency and the most recent transactions.<br>

• Cluster 1 is the lost customers who rarely place orders with the lowest amount of sales.<br>

• Cluster 0 encompasses at risk and loyal customers with medium value of frquency, recency and monetary.<br>

• High monetary value is correlated with high frequency of orders and more recent ones in all clusters.<br>
 
## **Recommendations:**

The company can create different marketing campaigns for the customer segments to grow revenue based on online retailer policies. In that sense, the company can offer incentives to low-value customers to keep them engaged and increase their frequency of orders. On the other hand, they can offer privileges such as exclusive discounts and early access to new products. Overall, it depends on what the company's business goal is.<br>
