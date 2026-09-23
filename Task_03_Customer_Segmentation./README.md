# Customer Segmentation Using K-Means Clustering

**EncoderX Data Science Internship – Batch 02 | Task 3**

A machine learning project for identifying customer segments based on demographic characteristics, annual income, and spending behavior.

## Objective

- Analyze customer demographic and spending characteristics.
- Perform data preprocessing and exploratory data analysis.
- Select relevant features and scale numerical variables.
- Determine a suitable number of customer clusters.
- Apply K-Means clustering.
- Visualize and interpret customer segments.
- Generate business insights and recommendations.

## Dataset

The project uses the **Mall Customers Dataset**, containing **200 customer records**.

Main features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

`CustomerID` is used only as an identifier and is not included in clustering. `Gender` is retained for exploratory analysis and interpretation, while Age, Annual Income, and Spending Score are used as the clustering features.

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Techniques

- StandardScaler
- K-Means Clustering
- Elbow Method
- Silhouette Score
- Principal Component Analysis (PCA)

## Project Workflow

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
