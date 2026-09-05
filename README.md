# Customer Churn & Retention Analysis

## 📊 Project Overview

This project analyses customer churn and retention patterns using a telecommunications customer dataset. The objective is to identify customer segments associated with higher churn and generate actionable insights that can support customer retention strategies.

The analysis was developed in Power BI using Power Query for data preparation and DAX for analytical measures.

## 🎯 Business Problem

Customer churn can negatively affect recurring revenue and long-term customer value. This analysis investigates:

- Which customer segments have the highest churn rates?
- How does churn vary by contract type and customer tenure?
- Is churn associated with service adoption and customer charges?
- Which areas could be prioritised for customer retention efforts?

## 🗂️ Dataset

The dataset contains **7,043 customer records** and includes demographic, service, contract, billing and churn-related information.

Key fields include:

- Customer demographics
- Customer tenure
- Contract type
- Internet and additional services
- Payment method
- Monthly and total charges
- Administrative and technical support tickets
- Churn status

🧹 Data Preparation

The dataset was prepared in Power Query before analysis. The main data preparation steps included:

- Removing duplicate records
- Checking for missing and inconsistent values
- Correcting data types
- Reviewing categorical fields for consistency
- Creating appropriate numerical and categorical fields for analysis
- Validating the dataset before loading it into the Power BI data model

These steps helped ensure that the dataset was suitable for reliable analysis and visualisation.

📊 Dashboard

The interactive Power BI dashboard provides an overview of customer churn patterns and highlights key factors associated with customer retention.

Key Dashboard Areas

- Overall customer churn rate
- Churn distribution by contract type
- Churn by customer tenure
- Churn by internet service
- Churn by payment method
- Customer charges and service patterns
- Customer demographic segments

The dashboard was designed to provide a clear view of churn patterns and help identify customer groups that may require targeted retention strategies.
## 📸 Dashboard Preview

![Customer Churn Dashboard](Customer_churn_dashboard.PNG)
## 🔍 Key Insights

The analysis identified several customer segments with substantially different churn patterns:

- **Overall churn:** 1,869 of 7,043 customers had churned, resulting in a churn rate of approximately **27%** and a retention rate of **73.5%**.

- **Contract type is strongly associated with churn:** Month-to-month customers had a **43% churn rate**, compared with **11%** for one-year contracts and only **3%** for two-year contracts. This suggests that customers without long-term commitments represent a key retention opportunity.

- **Newer customers show higher churn:** Customers with **0–12 months of tenure had the highest churn rate at 47%**. Churn declined progressively with tenure, reaching **10% among customers with 49+ months of tenure**.

- **Internet service differences:** Customers using **Fiber optic** had a churn rate of **42%**, compared with **19% for DSL** and **7% among customers without internet service**. This indicates that service type warrants further investigation when assessing churn risk.

- **Online security is associated with lower churn:** Customers without online security had a **42% churn rate**, compared with **15%** among customers with the service. Customers without internet service had the lowest rate at **7%**.

- **Churn varies across charge segments:** The **medium-charge segment recorded the highest churn rate at 59%**, followed by the low-charge segment at **38%** and the high-charge segment at **24%**. This suggests that customer charges may interact with other factors influencing retention.
## 💡 Business Recommendations

Based on the observed churn patterns, the following retention strategies could be considered:

- **Prioritise early-tenure customers:** Introduce targeted onboarding, engagement campaigns and early check-ins for customers within their first 12 months, where churn is highest.

- **Encourage longer-term contracts:** Develop incentives or personalised offers that encourage month-to-month customers to transition to one-year or two-year contracts.

- **Investigate fiber optic churn:** Review pricing, service quality, customer support and onboarding experiences for fiber optic customers to understand the factors contributing to their higher churn rate.

- **Promote online security services:** Consider targeted education, bundled offers or incentives for customers without online security, given the substantially higher churn rate observed in this segment.

- **Develop targeted retention strategies:** Use customer characteristics such as tenure, contract type, internet service and charge segment to identify higher-risk groups and tailor retention efforts accordingly.

- **Monitor churn regularly:** Establish recurring churn reporting and dashboard monitoring to track changes in customer behaviour and evaluate the effectiveness of retention initiatives.
## 🛠️ Tools & Technologies

- **Power BI** — Dashboard development and data visualisation
- **Power Query** — Data cleaning and transformation
- **DAX** — Analytical measures and calculations
- **Excel** — Data inspection and initial preparation
## 📌 Project Outcome

This project demonstrates the ability to take a raw customer dataset through the full analytics workflow — from data preparation and transformation to analytical modelling, dashboard development and insight generation.

The analysis highlights how customer characteristics and service attributes can be explored to identify higher-risk churn segments and inform data-driven customer retention strategies.
