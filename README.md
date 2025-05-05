# 🛍️ Retail Cluster: Customer Segmentation with K-Means

This project applies **K-Means Clustering** to segment customers based on their purchasing behavior using the **Online Retail II dataset**. It's a hands-on data science project aimed at helping businesses understand customer patterns through **Recency, Frequency, and Monetary (RFM)** analysis.

---

## 📊 Objective

To cluster customers of a UK-based online retailer into distinct segments using unsupervised learning, enabling targeted marketing and customer retention strategies.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository - Online Retail II
- **Details**: Includes transactional data from 2009–2011 for a UK-based online store
- **Fields**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

---

## 🔍 Methodology

1. **Exploratory Data Analysis (EDA)**
   - Identified null values, negative quantities/prices, and outlier stock codes
   - Visualized distributions and data anomalies

2. **Data Cleaning**
   - Removed cancellations, accounting records, null customers, and zero-priced items
   - Filtered based on proper invoice and stock code formats

3. **Feature Engineering**
   - Computed **RFM metrics**:
     - `Recency`: Days since last purchase
     - `Frequency`: Count of unique transactions
     - `Monetary`: Total purchase value
   - Removed outliers using IQR

4. **Scaling**
   - Applied **StandardScaler** to normalize features

5. **Clustering**
   - Used **Elbow Method** and **Silhouette Score** to find optimal `k = 4`
   - Applied **KMeans Clustering** to scaled RFM features

6. **Visualization**
   - 3D scatter plots for cluster distribution
   - Violin plots for cluster feature comparison

---

## 📌 Requirements

Install required libraries:

```bash
pip install -r requirements.txt
