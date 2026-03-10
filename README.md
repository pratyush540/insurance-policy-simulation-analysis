# Insurance Policy Simulation & Claims Analysis

This project simulates a car insurance portfolio and analyzes claim behavior, portfolio profitability, and risk exposure using Python and Power BI.

The goal of the project is to demonstrate how insurance data can be generated, analyzed, and visualized to understand claim trends and financial risk.

---

## Project Overview

The project includes:

- Simulation of **1,000,000 car insurance policies**
- Generation of a **claims dataset based on business rules**
- Analytical calculations using **Python (Pandas & NumPy)**
- Interactive **Power BI dashboard** for visualization

---

## Dataset Description

Two datasets were created for this project.

### 1. Policy Sales Data

Contains simulated insurance policy records including:

- Customer_ID
- Vehicle_ID
- Vehicle_Value
- Policy_Tenure
- Policy_Purchase_Date
- Policy_Start_Date
- Policy_End_Date
- Premium

Policy tenure distribution:

| Tenure | Distribution |
|------|------|
| 1 Year | 20% |
| 2 Years | 30% |
| 3 Years | 40% |
| 4 Years | 10% |

---

### 2. Claims Data

Claims were simulated using the following rules:

- Vehicles purchased on **7th, 14th, 21st, and 28th** of each month were considered defective
- **30% of these vehicles filed claims during 2025**
- Claim date occurs on **policy start date**
- **10% of 4-year policies filed additional claims in early 2026**

Claim amount:
₹10,000 (10% of vehicle value)


---

## Key Metrics Calculated

The analysis focuses on the following metrics:

- Total Premium Collected
- Monthly Claim Cost
- Loss Ratio (Claims / Premium)
- Claim Cost by Policy Tenure
- Claim Cost by Policy Sale Month
- Estimated Future Claim Liability
- Earned Premium

---

## Dashboard

A Power BI dashboard was created to visualize the portfolio performance.

Main visuals include:

- Monthly Claim Cost Trend
- Premium vs Claims by Policy Tenure
- Loss Ratio by Policy Tenure
- Loss Ratio by Policy Sale Month
- Portfolio KPIs

---

## Key Insights

- Claim activity is concentrated around policy start periods.
- The simulated portfolio shows a loss ratio greater than 1 due to high claim frequency assumptions.
- Short-tenure policies show relatively higher risk compared to longer policies.
- Significant future claim liability exists for vehicles that have not yet filed claims.

---

## Tools Used

- Python (Pandas, NumPy)
- Jupyter Notebook
- Power BI
- GitHub

---

## Files Included

- `policy_sales_data.csv`
- `claims_data.csv`
- `insurance_policy_simulation.ipynb`
- `insurance_policy_simulation.pbix`
- Project documentation

---

## Author

**Pratyush Anand**

Data Analyst | Python | SQL | Power BI
