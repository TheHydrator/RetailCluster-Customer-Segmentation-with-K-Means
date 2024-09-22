# RetailCluster: Customer Segmentation with K-Means

In this comprehensive data science project, we dive into a real-world dataset to uncover valuable insights about customer behavior using **K-means clustering**. The project is aimed at helping an online retailer better understand their customers through **RFM analysis** (Recency, Frequency, Monetary Value), allowing for more targeted marketing and improved customer retention strategies.

## Project Overview

The project utilizes the **Online Retail 2** dataset from the UC Irvine Machine Learning Repository, which contains customer transactions from an online retailer. Throughout the project, we handle challenges like missing data and outliers, and employ unsupervised learning techniques to segment customers based on their purchasing behavior. The ultimate goal is to generate actionable insights for the retailer to optimize their customer relationships.

## Key Steps in the Project

### 1. Data Exploration
- We explored the dataset to gain insights into the distribution of customer purchasing behavior, identifying key trends and anomalies.
- This step helped shape the approach to feature engineering and cleaning.

### 2. Data Cleaning
- Significant effort was placed on handling missing data and outliers. About 23% of the data was dropped during cleaning to ensure that we worked with high-quality, relevant information.
- We dealt with null values and anomalies to ensure a reliable dataset for the clustering process.

### 3. Feature Engineering
- The **RFM analysis** (Recency, Frequency, Monetary Value) technique was applied to create meaningful features that represent customer behavior.
- **Standard Scaling** was used to normalize these features, ensuring that each feature contributed equally to the clustering process.

### 4. K-Means Clustering
- We applied the **K-Means Clustering** algorithm to segment customers into different groups based on their purchasing behavior.
- Customers were grouped into clusters that provide insight into their value and engagement with the retailer.

### 5. Cluster Labels and Insights
- After clustering, we visualized the customer segments and assigned them meaningful labels based on the characteristics of each group:
  - **RETAIN**: High-value customers, who purchase regularly.
  - **RE-ENGAGE**: Customers who haven’t purchased recently but were frequent buyers before.
  - **NURTURE**: Customers with low spending, needing more engagement.
  - **REWARD**: Loyal and high-frequency buyers.
  - **PAMPER**: Customers who purchase infrequently but spend large amounts.
  - **UPSELL**: Customers with high potential for spending more.
  - **DELIGHT**: Customers with the highest spending and engagement.

### 6. Data Visualization
- We used data visualization techniques to represent the clusters, making it easy to interpret and act on the insights.
- Libraries like **Matplotlib**, **Seaborn**, and **pandas** were used to create visually compelling plots.

## Tools and Technologies

The following Python libraries were used in this project:
- **pandas**: For data manipulation and cleaning.
- **Matplotlib** and **Seaborn**: For data visualization.
- **scikit-learn**: For applying K-Means clustering and evaluating clusters.
- **openpyxl**: For working with Excel files.

## Key Takeaways

- This project highlights the power of **unsupervised learning** techniques, like K-Means, in deriving actionable insights from large datasets.
- The segmented customer groups provide a clear path for the retailer to apply targeted marketing strategies such as loyalty programs, re-engagement campaigns, and upselling opportunities.
- By understanding customer behavior through **RFM analysis**, retailers can make more informed decisions, enhance customer experiences, and ultimately drive more revenue.
