
# Customer Segmentation Using K-Means Clustering

##  Project Overview

This project focuses on customer segmentation using **K-Means clustering**. The goal is to identify groups of customers with similar demographic and spending characteristics.

The analysis uses customer **Age, Annual Income, and Spending Score** to identify meaningful customer segments that can support targeted marketing and customer engagement strategies.

---

##  Objective

The main objectives of this project are to:

- Analyze customer demographic and spending characteristics
- Preprocess and scale numerical features
- Explore customer behavior through EDA and visualizations
- Determine a suitable number of clusters
- Apply K-Means clustering
- Visualize and interpret customer segments
- Provide business insights and recommendations

---

##  Dataset

The project uses the **Mall Customers Dataset**, containing 200 customer records.

### Features

| Feature | Description |
|---|---|
| CustomerID | Unique identifier for each customer |
| Gender | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands of dollars |
| Spending Score (1-100) | Spending behavior score |

`CustomerID` is used only as an identifier and is not included in clustering. `Gender` is retained for exploratory analysis and interpretation, while the K-Means model uses the numerical features.

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Machine Learning Techniques

- StandardScaler
- K-Means Clustering
- Elbow Method
- Silhouette Score
- Principal Component Analysis (PCA)

---

##  Project Workflow

```text
Dataset
   ↓
Data Inspection
   ↓
Data Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Feature Scaling
   ↓
Elbow Method + Silhouette Score
   ↓
K-Means Clustering
   ↓
Cluster Visualization
   ↓
PCA Visualization
   ↓
Segment Interpretation
   ↓
Business Insights & Recommendations
