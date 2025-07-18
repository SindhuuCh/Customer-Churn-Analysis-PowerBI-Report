# 🧠 Banking Customer Churn Analysis Dashboard – Power BI

This project presents an interactive **Customer Churn Analysis Dashboard** built using **Power BI**. It analyzes a fictional bank’s customer data to identify patterns and key factors contributing to customer churn. The goal is to help the bank understand which customer segments are at risk of leaving and support strategic decisions to improve retention.

---

## 📌 Project Objective

Customer churn directly impacts profitability. This project identifies the driving factors behind customer exits and provides actionable insights through a comprehensive dashboard. It uses data-driven storytelling to visualize how demographics, credit behavior, and account activity affect customer retention.

---

## 📊 Dashboard Overview

The Power BI report includes:

- Total Customers, Active vs Inactive
- Credit Card Holders vs Non-Holders
- Exit vs Retained Customer distribution
- Churn breakdown by:
  - Gender
  - Age
  - Geography
  - Credit Score
  - Tenure
  - Number of Products
  - Account Balance
- Interactive filters for Year, Month, Geography, and Gender

---

## 📄 Business Requirement Document (BRD)

The dataset includes several attributes related to customer demographics and financial activity. Key fields include:

- **CreditScore**: Higher scores indicate lower churn risk.  
  Ranges:  
  - Excellent: 800–850  
  - Very Good: 740–799  
  - Good: 670–739  
  - Fair: 580–669  
  - Poor: 300–579

- **Geography**: Regional differences impact churn patterns.
- **Gender**: Used to analyze gender-based churn trends.
- **Age**: Older customers generally show more loyalty.
- **Tenure**: Longer banking relationships reduce churn risk.
- **Balance**: Higher balances indicate more engagement.
- **NumOfProducts**: More products = more customer stickiness.
- **HasCrCard**: Credit card ownership reduces churn probability.
- **IsActiveMember**: Active customers are less likely to churn.
- **EstimatedSalary**: Compared to churn behavior for additional insight.
- **Exited**: Target variable (0 = Retained, 1 = Exited)
- **Bank DOJ**: Date of joining to track tenure.

---

## 📂 Data Sources

The analysis was performed using the following files:

- `Bank_Churn.csv`
- `ActiveCustomer.xlsx`
- `ExitCustomer.xlsx`
- `CreditCard.xlsx`
- `CustomerInfo.csv`
- `Gender.xlsx`
- `Geography.xlsx`

All files are available in the `/DataSets/` folder.

---

## 🛠️ How to Run the Report

1. Clone or download this repository.
2. Open `Customer Churn Analysis Report.pbix` in **Power BI Desktop**.
3. Ensure the data files are in the `/DataSets/` directory.
4. Click **Refresh** to load the latest data.
5. Use slicers and visuals to explore churn trends and segment breakdowns.

---


