 **Telco Customer Churn Analysis**

1.Project Overview

This project explores a real-world dataset from a telecom company to analyze **customer churn** — the phenomenon of customers leaving the service. The goal is to identify patterns and key factors that contribute to churn, which can help the business improve customer retention.

Using Python, we performed data cleaning and exploratory data analysis (EDA) on 7,043 customer records.I visualized trends around tenure, contract type, and payment method to uncover actionable insights.


2. Dataset

- **Source**: Telco Customer Churn dataset (commonly available on Kaggle)
- **Rows**: 7,043 customers
- **Columns**: 21 customer-related features

3. Key Variables:
- `Churn`: Whether the customer left within the last month
- `tenure`: Number of months the customer has stayed
- `Contract`: Type of customer contract (Month-to-month, One year, Two year)
- `PaymentMethod`: How the customer pays (e.g., Electronic check)
- `MonthlyCharges` and `TotalCharges`: Billing amounts


4. Data Cleaning

- Converted `TotalCharges` to numeric (11 non-numeric values fixed)
- Dropped 22 duplicate rows
- Removed `customerID` as it’s non-informative
- Handled null values and ensured data types were consistent


5.Exploratory Data Analysis (EDA)

### 1. Churn Distribution

- About 26% of customers have churned.


### 2. Churn by Contract Type

- **Month-to-month** customers are much more likely to churn.
- Long-term contracts show much lower churn.


### 3. Tenure vs Churn

- Customers who churn usually have a **tenure under 12 months**.


### 4. Monthly Charges vs Churn

- Churners often pay higher monthly charges.

### 5. Payment Method

- Customers using **Electronic Check** churn at a much higher rate.

6. Key Findings

- Customers with short tenure and month-to-month contracts are most likely to churn.
- Higher monthly charges and electronic payment methods are associated with churn.
- Long-term contract users are more stable.


7. Tools Used

- **Language**: Python
- **Libraries**: pandas, matplotlib, seaborn
- **Platform**: Jupyter Notebook






