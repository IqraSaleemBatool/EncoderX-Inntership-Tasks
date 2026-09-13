# Sales Forecasting Using Machine Learning

**EncoderX Data Science Internship – Batch 02 | Task 2**

A machine learning project for forecasting daily store sales using historical sales data.

## Objective

* Analyze historical sales patterns.
* Perform data preprocessing and EDA.
* Create time-based and lag features.
* Compare machine learning models.
* Forecast sales and generate business insights.

## Dataset

The dataset contains daily sales data for **10 stores from 2022–2023**.

Main features:

* Date
* Store
* Sales
* Promotion
* Holiday

## Models

Two models were compared:

* Linear Regression
* Random Forest Regressor

### Results

| Model             |  MAE | RMSE |    R² |
| ----------------- | ---: | ---: | ----: |
| Linear Regression | 7.25 | 8.95 | 0.867 |
| Random Forest     | 5.54 | 6.97 | 0.920 |

**Random Forest performed better** and was used for the final forecasting.

### Final Test Result

* MAE: **6.63**
* R²: **0.877**

## Important Features

* Day of week – **27.5%**
* Holiday – **23.3%**
* Promotion – **22.2%**
* 30-day rolling average – **20.3%**

## Key Insights

* Promotions and holidays are associated with higher sales.
* Weekday sales were higher than weekend sales.
* Recent sales trends were important for forecasting.
* The model can support inventory, marketing, and staffing decisions.

## Project Structure

```text
Task 2/
├── Sales_Forecasting.ipynb
├── Sales_Forecasting_Report.pdf
├── requirements.txt
│
├── data/
│   └── cleaned_sales.csv
│
├── models/
│   ├── linear_regression.pkl
│   ├── random_forest.pkl
│   └── preprocessor.pkl
│
├── results/
│   └── forecast_results.csv
│
└── plots/
    ├── actual_vs_predicted.png
    ├── sales_forecast.png
    └── feature_importance.png
```

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab Notebook

