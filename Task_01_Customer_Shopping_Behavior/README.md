# Customer Shopping Behavior Analysis

##  Project Overview

This project performs Exploratory Data Analysis (EDA) on a customer shopping behavior dataset.

The main objective is to understand customer demographics, product preferences, purchasing patterns, spending behavior, and relationships between different variables.

The project was completed as part of the **EncoderX Remote Internship – Data Science, Batch 02**.

---

##  Objectives

The main objectives of this project are:

- Understand the structure of customer shopping data.
- Clean and preprocess the dataset.
- Analyze customer demographics.
- Identify popular products and categories.
- Analyze customer spending behavior.
- Examine purchase frequency and subscription behavior.
- Identify relationships between numerical variables.
- Create meaningful data visualizations.
- Generate actionable business insights and recommendations.

---

##  Dataset

The dataset contains customer shopping information such as:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Payment Method
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Preferred Payment Method
- Frequency of Purchases

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

##  Data Preprocessing

The following preprocessing activities were performed:

- Checked missing values
- Checked duplicate records
- Verified data types
- Examined data consistency
- Analyzed numerical variables
- Examined potential outliers
- Created age groups for demographic analysis

The cleaned dataset is included in the repository.

---

##  Exploratory Data Analysis (EDA)

The analysis covers:

### Customer Demographics
- Gender distribution
- Age distribution
- Age groups

### Product & Category Analysis
- Most purchased items
- Purchases by category
- Average purchase amount by category
- Category comparison

### Customer Spending
- Purchase amount distribution
- Spending patterns

### Purchase Behavior
- Subscription status
- Purchase frequency
- Purchase frequency vs spending

### Relationship Analysis
- Previous purchases vs purchase amount
- Correlation between numerical variables

---

##  Visualizations

The project includes the following visualizations:

- Bar Charts
- Line Chart
- Histogram
- Scatter Plot
- Correlation Heatmap

These visualizations were created using Matplotlib and Seaborn.

---

##  Key Insights

The analysis revealed several important patterns:

- Product popularity varies across categories.
- Purchase frequency and average spending are not necessarily the same.
- Customer purchasing behavior varies across different customer groups.
- Previous purchases have a weak relationship with current purchase amount.
- Numerical variables show very weak linear correlations.
- Multiple customer attributes should be considered when analyzing shopping behavior.

---

##  Recommendations

Based on the analysis:

- Focus marketing on popular products and categories.
- Promote higher-value products through targeted campaigns.
- Use customer segmentation for personalized marketing.
- Encourage repeat purchases through loyalty and subscription programs.
- Use purchasing frequency to design targeted promotions.
- Consider multiple customer attributes when making business decisions.

---

##  Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.ipynb
├── cleaned_customer_shopping_behavior.csv
├── README.md
├── report.pdf
├── shopping_trends.csv
