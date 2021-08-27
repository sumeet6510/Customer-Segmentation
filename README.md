# Customer-Segmentation
Online Retail Customer Segmentation - Unsupervised Machine Learning Project

Problem Description -
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

# Online_Retail_Customer_Segmentation
# The need of customer segmentation:
The differences in customers' behaviour, demographics, geographies, etc. help in classifying them in groups. Learning about different groups in the customer can help with following:

Target Marketing
Client understanding
Optimal product placement
Searching for new customers
Revenue growth

# Recency-Frequency-Monetary (RFM) model to determine customer value:
The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

Recency – How recently did the customer purchase?
Frequency – How often do they purchase?
Monetary Value – How much do they spend?
A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer.

# Segmentation with K-means clustering:
Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton.
Then, the unsupervised classification technique, K-means clustering algorithm, is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm.
The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.
# Conclusion
• K-Means Clustering with Silhouette gives the highest score of 
65% for number of clusters 3.

• Sales has been increased from 2010 to 2011.

• RFM for Cluster ID box plots tells well about Cluster detail.

Conclusion of project - 
Dataset consists of 541909 rows and contains 8 different features. Data were present from 38 different countries but United Kingdom had almost 91% of data. There were 4372 different customers data were present. From Silhouette Analysis we find the optimum value of** k =3. So,we divide customers into 3 groups. **From Kmeans clustering Algorithm we found that - Group 1 customers have very low Recency while group 2 customers have very high Recency. Also in Kmeans - Group 1 customers have high Monetary Value and Frequency. From Hierarchical clustering algorithm we came to conclusion that - Group 1 customer have high Recency rate but Group 2 customers have high Monetary and Frequency.
To conclude, we saw how we can segment our customer depending on our business requirements. You can perform RFM for your entire customer base, or just a subset. For example, you may first segment customers based on a geographical area or other demographics, and then by RFM for historical, transaction-based behaviour segments. RFM analysis can help in answering many questions with respect to their customers and this can help companies to make marketing strategies for their customers, retaining their slipping customers and providing recommendations to their customer based on their interest. We used the K-means algorithm to segment our customer in various clusters having similar similarity. I think K-means did a pretty good job here.

Summary of Project - 
RFM analysis can segment customers into homogenous group quickly with set of minimum variables. Scoring system can be defined and ranged differently. We get a better result for clustering steps by applying scoring rather than using the raw calculated RFM values. Therefore, segmenting should be done by RFM scoring and further analysis on the spending behavior should be done on the raw values for the targeted cluster to expose more insight and characteristics. RFM analysis solely depends on purchasing behavior and histories, analysis can be further improved by exploring weighted composite scoring or including customer demographic information and product information. A good analysis can increase effectiveness and efficiency of marketing plans, hence increase profitability at minimum cost
