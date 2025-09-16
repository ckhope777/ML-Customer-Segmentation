# ML-Customer-Segmentation
Unsupervised ML project to cluster bank customers by spending patterns and interactions, uncovering actionable insights for targeted marketing and customer service optimization.

## Project Overview

Banks need to understand their customers to design effective marketing and service strategies. However, customers vary widely in spending habits, product usage, and interactions with the bank. Without data-driven segmentation, campaigns remain generic and less impactful.

This project applies machine learning clustering techniques to uncover natural customer groups. By analyzing transaction data and interaction history, we identify meaningful segments and provide the bank with strategic recommendations for better marketing, cross-selling, and service delivery.

## Tools & Technologies

- Python 
- Pandas, NumPy → data preprocessing & feature engineering
- Matplotlib, Seaborn → data visualization & EDA
- Scikit-learn → machine learning algorithms:

- K-Means Clustering
     - Elbow Method & Silhouette Score for optimal k selection
     - StandardScaler for normalization
     - PCA for dimensionality reduction and visualization
  
## Approach & Methodology

1. Problem Understanding
     - Objective: Group customers into distinct clusters based on spending behavior and bank interactions.
     - Value: Enable the bank to design personalized marketing campaigns and improve service delivery.

2. Data Preprocessing
     - Cleaned missing values and outliers.
     - Normalized features to ensure equal weight across variables.

3. Exploratory Data Analysis (EDA)
     - Visualized spending habits, frequency of transactions, and product adoption.
     - Identified early hints of segmentation (e.g., high-spenders, digital-first, branch-dependent).

4. Clustering
     - Applied K-Means clustering on preprocessed data.
     - Used Elbow Method and Silhouette Score to select optimal cluster number.
     - Visualized clusters in 2D using PCA.
5. Insights & Recommendations
  - Discovered distinct segments such as:
       - High-value premium clients (require exclusive offers, loyalty programs).
       - Digital adopters (promote app features, online services).
       - Traditional customers (need better in-branch experience & education on digital banking).
  - Recommended targeted marketing strategies and service personalization for each segment.

6. Results & Business Impact
     - Segmented customers into 3 actionable clusters.
     - Identified strategies to boost cross-sell opportunities, improve customer satisfaction, and increase retention.
     - Demonstrated how unsupervised ML models can directly support business decision-making. 
