# HR Analytics Dashboard | Employee Attrition Analysis

## Project Overview

This project focuses on analyzing employee attrition using HR data to identify workforce trends and understand factors associated with employee turnover.

An interactive **Power BI dashboard** was developed to explore employee demographics, job-related characteristics, satisfaction levels, income groups, and attrition patterns. The dashboard provides an overview of workforce composition and helps identify areas that may require further HR investigation.

## Objectives

* Analyze overall employee attrition and retention.
* Identify attrition patterns across departments and job roles.
* Explore the relationship between employee demographics and attrition.
* Examine attrition across income, age, and tenure groups.
* Develop an interactive dashboard for HR data exploration.

## Dataset

* **Dataset:** IBM HR Employee Attrition Dataset
* **Total Records:** 1,470 employees
* **Total Features:** 33 columns after preprocessing and feature engineering.
* **Target Variable:** Attrition

The dataset includes employee information such as age, department, job role, monthly income, job satisfaction, overtime, years at company, and attrition status.

Additional categorical features were created to support analysis, including:

* Age Group
* Income Group
* Tenure Group

## Tools & Technologies

* **Microsoft Excel:** Dataset inspection and handling.
* **Python:** Data cleaning, preprocessing, and feature engineering.
* **Pandas & NumPy:** Data manipulation and analysis.
* **Power BI:** Interactive dashboard development and visualization.
* **DAX:** KPI calculations and measures.

## Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

| KPI                      |     Value |
| ------------------------ | --------: |
| Total Employees          |     1,470 |
| Employees Left           |       237 |
| Attrition Rate           |    16.12% |
| Average Monthly Income   | $6,502.93 |
| Average Years at Company |      7.01 |

## Dashboard Analysis

The dashboard explores employee attrition through the following visualizations:

1. Attrition Rate by Department
2. Attrition Rate by Job Role
3. Attrition Rate by Age Group
4. Attrition Rate by Income Group
5. Employees Left by Overtime
6. Attrition Rate by Job Satisfaction
7. Attrition Rate by Tenure Group
8. Employees by Gender

### Interactive Filters

Users can explore the data through filters for:

* Department
* Job Role
* Gender
* Age Group
* Overtime

The dashboard visuals and KPI measures respond to the selected filters, allowing users to explore different employee groups.

## Key Metrics

* **Employees Staying:** 1,233
* **Retention Rate:** 83.88%

These metrics complement the attrition KPIs and provide an overview of employee retention.

## Project Structure

```text
HR-Analytics-Dashboard/
│
├── HR_Analytics_Dashboard.ipynb
│
├── HR_Analytics_Dashboard.pbix
│
├── HR_Analytics_Cleabed.csv
│
├── WA_Fn-UseC_-HR-Employee-Attrition
│
└── README.md
```

*Note: Adjust the folder and file names in this structure to match your actual repository.*

## Project Outcome

This project demonstrates how HR data can be transformed into an interactive analytical dashboard. It provides insights into employee attrition patterns and workforce characteristics through KPI tracking, data visualization, and interactive filtering.

## Future Improvements

* Add more detailed analysis of factors associated with employee attrition.
* Improve dashboard design and visual presentation.
* Incorporate additional HR performance metrics.
* Explore predictive modeling for employee attrition.

---

**Project Category:** Data Analytics | HR Analytics | Business Intelligence


