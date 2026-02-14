# Customer Segmentation Using K-Means Clustering

## Project Overview
This project segments mall customers based on their demographic and spending behavior using unsupervised learning. 
The insights derived from the clusters are used to develop targeted marketing strategies.

## Objective
- Perform Exploratory Data Analysis (EDA) on customer data
- Apply K-Means clustering for segmentation
- Use PCA for cluster visualization
- Suggest actionable marketing strategies based on cluster behavior

## Dataset
- Mall Customers Dataset (CSV)
- Features: CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100)

## Methodology
1. **Data Cleaning & Preprocessing**: Remove duplicates and handle missing values.
2. **Exploratory Data Analysis**: Pairplots and correlation analysis.
3. **Feature Scaling**: Standardize numerical features for clustering.
4. **K-Means Clustering**: Use the Elbow method to select optimal number of clusters.
5. **PCA Visualization**: Reduce dimensions to 2D for easy cluster visualization.
6. **Cluster Analysis & Strategy**: Examine cluster characteristics and recommend marketing strategies.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Results
- Identified **5 distinct customer segments** based on income, age, and spending behavior.
- Developed **targeted marketing strategies** for each cluster.

| Cluster | Characteristics                    | Marketing Strategy |
|---------|-----------------------------------|------------------|
| 0       | High income, high spending        | Premium memberships, luxury promotions |
| 1       | High income, low spending         | Personalized engagement campaigns |
| 2       | Low income, high spending         | Discount bundles, reward programs |
| 3       | Young, moderate spending          | Social media campaigns, flash sales |
| 4       | Conservative spenders             | Value-for-money products, seasonal promotions |


## Author
Dua Ilyas

## GitHub Repository
https://github.com/DuaIlyas24/mall-customer-segmentation/tree/main


