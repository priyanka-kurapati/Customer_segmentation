🧩 Customer Segmentation Using RFM and K-Means Clustering
This project applies RFM (Recency, Frequency, Monetary) analysis and K-Means clustering to segment customers based on their purchasing behavior. It provides insights that can help businesses tailor marketing strategies and increase customer retention.

📊 General Information
This project explores two customer segmentation strategies:
RFM Scoring + K-Means Clustering:
Customers are scored based on RFM values (e.g., 1–5), and then grouped into clusters using K-Means.
Raw RFM Values + K-Means Clustering:
Raw Recency, Frequency, and Monetary values are used directly for clustering without scoring.
Both approaches aim to uncover distinct customer profiles based on historical transaction behavior.

📁 Dataset
Sample retail sales data over 3 years
Source: Kaggle Dataset - Sample Sales Data
The dataset includes transaction data such as invoice number, date, customer ID, quantity, unit price, and more.

🎯 Motivation
Customer segmentation enables businesses to:
Better understand customer behavior
Design targeted marketing strategies
Improve personalization and increase sales
RFM segmentation is one of the most popular techniques used in marketing analytics. It categorizes customers based on:
Recency (R): How recently a customer made a purchase
Frequency (F): How often they purchase
Monetary (M): How much money they spend
These metrics help identify loyal customers, potential churners, high-value clients, etc.

📂 Project Structure
📦Customer_Segmentation_RFM_KMeans
├── Customer_segmentation.ipynb     # RFM scoring + K-Means
├── Segmentation_Kmeans.ipynb       # Raw RFM values + K-Means
├── customers_segments.py           # Python script version
├── README.md
└── requirements.txt (optional)

🛠️ Technologies Used
Python 3.6+
Libraries:
pandas, numpy for data manipulation
matplotlib, seaborn for visualization
sklearn for machine learning (KMeans)
scipy for statistics

📈 Results
The output includes:
Optimal number of clusters using Elbow Method
Cluster visualizations (2D and 3D plots)
Cluster profiles showing characteristics of each customer group
