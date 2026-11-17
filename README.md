# customer-churn-analysis


Project Overview

This project analyzes customer churn in a telecommunications company using Python, SQL, and data visualization.

The main goal is to identify customer segments with higher churn rates and discover patterns that may help the business improve customer retention.

Dataset

- Source: IBM Telco Customer Churn Dataset
- Rows: 7,043 customers
- Columns: 21
- Target Variable: Churn

Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL (SQLite)
- Jupyter Notebook

Project Workflow

1. Data loading and exploration
2. Data quality checks
3. Data cleaning and preprocessing
4. Exploratory Data Analysis (EDA)
5. Customer churn analysis
6. Data visualization
7. SQL analysis using SQLite
8. Business insights and recommendations

Key Findings

Overall Churn

- Total customers: 7,043
- Churned customers: 1,869
- Overall churn rate: 26.54%

Churn by Contract Type

- Month-to-month: 42.71%
- One year: 11.27%
- Two year: 2.83%

Churn by Internet Service

- Fiber optic: 41.89%
- DSL: 18.96%
- No internet service: 7.40%

Churn by Payment Method

- Electronic check: 45.29%
- Mailed check: 19.11%
- Bank transfer (automatic): 16.71%
- Credit card (automatic): 15.24%

Customer Tenure

- Average tenure of retained customers: 37.57 months
- Average tenure of churned customers: 17.98 months

Monthly Charges

- Average monthly charges of retained customers: 61.27
- Average monthly charges of churned customers: 74.44

Business Insights

1. Month-to-month customers have a significantly higher churn rate than customers with long-term contracts.
2. Fiber optic customers show a higher churn rate compared with other internet service groups.
3. Electronic check users have the highest churn rate among payment method groups.
4. Customers who leave the company tend to have shorter tenure.
5. Customers who churn also have higher average monthly charges.

Recommendations

- Improve retention strategies for month-to-month customers.
- Investigate service quality and customer satisfaction among fiber optic users.
- Review the customer experience for electronic check users.
- Introduce onboarding and retention programs for new customers.
- Review pricing and service value for customers with higher monthly charges.

Repository Structure

customer-churn-analysis/
├── data/
│   └── telco_customer_churn.csv
├── notebooks/
│   └── customer_churn_analysis.ipynb
├── sql/
│   └── churn_analysis.sql
├── .gitignore
├── requirements.txt
└── README.md

How to Run

1. Clone the repository.
2. Install the required libraries:

pip install -r requirements.txt

3. Open the Jupyter Notebook:

jupyter notebook

4. Run the cells in "notebooks/customer_churn_analysis.ipynb".

Data Source

IBM Telco Customer Churn Dataset:

https://github.com/IBM/telco-customer-churn-on-icp4d

Disclaimer

This project is for educational and analytical purposes. The findings describe associations in the dataset and do not establish causal relationships.

Author

GitHub: https://github.com/mobo2r-ali