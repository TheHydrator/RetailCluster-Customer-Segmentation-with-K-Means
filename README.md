# RetailCluster-Customer-Segmentation-with-K-Means

This project focuses on segmenting customer data from an online retail dataset using the **K-Means Clustering** algorithm. The aim is to group customers into distinct clusters based on their purchasing behavior, which can help businesses design targeted marketing strategies for each customer group.

## Project Steps

### 1. Data Exploration
- We explored the dataset to understand customer purchasing behavior.
- Key features include:
  - **Monetary Value**: Total amount spent by customers.
  - **Frequency**: Number of purchases made by customers.
  - **Recency**: How recently a customer made a purchase.

### 2. Data Cleaning
- About 23% of the data was cleaned and filtered out to remove irrelevant records, ensuring accuracy in the analysis.

### 3. K-Means Clustering
- The **K-Means** algorithm was used to create customer clusters.
  - **Step 1**: Randomly initialized centroids.
  - **Step 2**: Assigned each customer to the nearest centroid.
  - **Step 3**: Iteratively updated centroids until the clusters converged.

### 4. Feature Engineering
- We applied **Standard Scaling** to the features, ensuring that the data had a mean of 0 and a standard deviation of 1.
- This transformation allowed each feature to contribute equally to the clustering process.

### 5. Evaluation with Silhouette Score
- We evaluated the quality of the clusters using the **Silhouette Score**.
- The score ranges from **-1 to 1**:
  - A score closer to **1** indicates well-separated and distinct clusters.
  - A score near **0** suggests overlapping clusters, and a score below **0** could indicate misclassification.

## Conclusion
This clustering approach helps identify different customer segments, such as high-value customers or infrequent buyers, and enables businesses to target each group with appropriate marketing strategies, such as loyalty programs or re-engagement campaigns.

