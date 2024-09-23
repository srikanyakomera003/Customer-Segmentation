# Customer Segmentation using RFM Method and K-Means Clustering

# Project Overview
This project performs customer segmentation by combining the RFM (Recency, Frequency, Monetary Value) method with K-Means clustering. The dataset used includes sample sales data from retail analytics, covering three years of sales.

# Customer Segmentation
Customer segmentation is a powerful strategy that allows businesses to better understand their clients and tailor marketing efforts to meet diverse needs. By analyzing shopping data, companies can execute targeted campaigns that increase sales and improve customer retention. The RFM analysis is one of the most widely used techniques, allowing for the creation of personalized offers.

# RFM Analysis
Recency: Days since the last purchase.
Frequency: Total number of purchases.
Monetary Value: Total money spent.
Customers are assigned scores ranging from 1 (lowest) to 4 (highest) based on these criteria.

# Dataset
The dataset can be found here.

# Steps Involved
Import Libraries and Load Dataset
Data Cleaning and Preparation
Data Analysis and Visualization
RFM Analysis
Model: RFM Scoring + K-Means Clustering
Description of Results
# Import Libraries and Data

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import datetime as dt
from sklearn.cluster import KMeans
# Data Cleaning
Unnecessary columns such as ADDRESSLINE1, ADDRESSLINE2, POSTALCODE, etc., are removed. The PRODUCTCODE is simplified to its initial three characters.

# Basic Data Analysis
Unique values and missing values are checked to understand the dataset better.

# Data Visualization
Data is plotted to visualize distributions and trends over the years.

# RFM Analysis
The RFM table is created by calculating Recency, Frequency, and Monetary Value for each customer.

# K-Means Clustering
K-Means clustering is performed to segment customers into groups based on their RFM scores.

# Results Interpretation
The analysis resulted in four customer segments:

Group 0: Departing customers who have not shopped recently.
Group 1: Active customers who shop frequently and spend more.
Group 2: Inactive customers who rarely purchase.
Group 3: New customers who have made recent but infrequent purchases.
# Marketing Strategies
For Group 1 (Active): Special offers, discounts, loyalty programs.
For Group 3 (New): Email marketing and introductory offers.
For Group 0 (Departing): Re-engagement campaigns to win back former customers.
For Group 2 (Inactive): Targeted promotions to reactivate interest.
# Conclusion
This project highlights the importance of customer segmentation and provides actionable insights for targeted marketing strategies.
