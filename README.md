# Customer_Churn_Analysis

## Project Overview
This project analyzes customer churn for a telecommunications company using the [Kaggle's Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)). The goal is to identify key drivers of churn, visualize insights, and build a predictive model to help reduce customer attrition.

## Tools Used
- **Python**: Pandas for data manipulation, Seaborn/Matplotlib for visualization, Scikit-learn for logistic regression.
- **Power BI**: Interactive dashboard for churn insights.
- **GitHub**: Documentation and code sharing.

## Dataset
The dataset contains customer information (e.g., tenure, contract type, monthly charges) and a target variable `Churn` (Yes/No). It has 7,043 rows and 21 columns.

## Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Cleaned the dataset (handled missing values, converted categorical variables).
   - Visualized churn distribution, tenure vs. churn, and correlations.
   
2. **Predictive Modeling**:
   - Built a logistic regression model to predict churn.
   - Achieved an accuracy of approximately 81.55% (see script output).

3. **Dashboard**:
   
     
## Key findings
- Customers with shorter tenure and month-to-month contracts are more likely to churn.


## Files
- `churn_analysis.py`: Python script for EDA and modeling.
- `processed_churn_data.csv`: Cleaned dataset for Power BI.
- `churn_distribution.png`: Churn count visualization.
- `tenure_vs_churn.png`: Tenure vs. churn box plot.
- `correlation_heatmap.png`: Correlation heatmap.
- `dashboard1.png`: Power BI dashboard screenshot.
-

## How to Run
1. **Python Script**:
   - Install Python and required libraries: `pip install pandas seaborn matplotlib scikit-learn`.
   - Download the dataset from Kaggle and place it in the project folder.
   - Run `Customer_churn_analysis.ipynb`.

2. **Power BI Dashboard**:
  

## Results
- **EDA Insights**:
  - ~26% of customers churned.
  - Short tenure and month-to-month contracts are strong churn drivers.
- **Model Performance**: Logistic regression achieved ~81.55% accuracy.
- **Dashboard**: 

## Screenshots
![Churn Distribution](churn_distribution.png)
![Tenure vs Churn](tenure_vs_churn.png)
![Correlation Heatmap](correlation_heatmap.png)
![Power BI Dashboard](dashboard1.png)

## Future Improvements
- Experiment with advanced models (e.g., Random Forest, XGBoost).
- Add more interactive filters to the Power BI dashboard.
- Analyze additional features like customer support interactions.

## Contact
Feel free to reach out via [Your Email] or [Your LinkedIn] for questions or collaboration.
