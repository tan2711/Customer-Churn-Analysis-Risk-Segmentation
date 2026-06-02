# Telecom Customer Churn Analysis

# Summary

This project analyzes telecom customer data to understand what’s really driving customer churn, particularly contract type, tenure, monthly charges, and measures they impact customer retention.
For prepping of data Microsoft Excel was used, after which an interactive Power BI dashboard was built to segment customers and track churn patterns.
The analysis identified an overall 26% churn rate, with month-to-month customers forming the majority of high-risk users, highlighting contract type as the strongest predictor of churn.

## Quick Links
- [Power BI Dashboard](https://app.powerbi.com/groups/me/reports/aa6b150e-34ad-4138-b84e-58bf8c109717?ctid=27282fdd-4c0b-4dfb-ba91-228cd83fdf71&pbi_source=linkShare)
- [Cleaned Dataset](https://github.com/tan2711/Customer-Churn-Analysis-Risk-Segmentation/blob/a4d27e79b4c38f88a9f3511b2d481dd90e52fb7d/Telecom%20churn%20dataset.csv)
  

## Data Preparation (Microsoft Excel)

### Dataset
Telecom Customer Churn Dataset (3000+ customers)
Columns: Customer ID, Gender, InternetService, TechSupport, Contract, PaymentMethod, MonthlyCharges, TotalCharges, Churn

### Data cleaning steps
- Cleaned the dataset by removing null, duplicate, and inconsistent records to ensure data accuracy
- Standardized Churn column values to “Yes”/ “No”
- Aligned data types (Tenure, Monthly Charges) to make aggregation reliable
- Verified data consistency to improve accuracy and reliability of the analysis

## Analysis Steps (Power BI)

### Workflow:
- Imported and modeled the cleaned dataset in Power BI
- Created key measures like Churn Rate and Risk Segments
- Grouped customers into High, Medium, and Low risk based on tenure, contract type, and monthly charges
- Built a three-page interactive dashboard to understand churn patterns and support informed business decisions

### Key Visualizations:
**Page 1 - Churn Overview:** Customer Distribution by Churn, Churn by Contract Type, Churn by Internet Service
<img width="922" height="517" alt="image" src="https://github.com/user-attachments/assets/43cc8d20-e50b-425e-ae04-f7f74973098a" />

**Page 2 - Risk Analysis:** Risk Distribution, Tenure Impact, Churn Rate by Monthly Charges, High-Risk Table
<img width="921" height="513" alt="image" src="https://github.com/user-attachments/assets/c5ba8c06-eae1-4efe-a08b-c8b8982f1de6" />


**Page 3 - Insights:** High Risk Customers by Contract
<img width="915" height="510" alt="image" src="https://github.com/user-attachments/assets/690cdf65-322c-40c3-9fe8-aef3f7c8c195" />


## Insights

Overall, the company experiences a churn rate of 26%, highlighting customer retention challenges.
Month-to-month contracts are the biggest churn driver, making contract type a key predictor of churn.  
Customers with tenure below 12 months represent the highest-risk segment, showing that retention is most challenging during the early stages.
Churn reaches nearly 38% among customers with monthly charges between 80–100, suggesting that higher-paying customers may be more price sensitive.
Customers with longer tenure and long-term contracts tend to show stronger loyalty over time, depicting the importance of long-term customer engagement strategies.

## Recommendations

Encourage long-term contract adoption
Since month-to-month customers are more likely to churn, the business can encourage long-term subscriptions by offering bundled services, loyalty benefits, and contract-based discounts.

Strengthen early-stage onboarding
Customers within the first 12 months show the highest churn risk, making it important to improve the onboarding experience through regular follow-ups, customer support, and guidance on service usage.

Address price sensitivity among high-paying customers
Customers with higher monthly charges tend to churn more frequently, suggesting the need for personalized offers, flexible pricing options, and incentives that provide better value to high-value users.

Build customer loyalty through proactive engagement and retention programs
Building stronger customer relationships through personalized communication, loyalty rewards, and proactive customer support can help improve customer loyalty and reduce churn among high-risk users.

## Dashboard Summary

The analysis shows that focusing on high-risk segments, particularly new and high-paying customers, can improve customer retention and long-term customer value.

## Conclusion

This project shows how raw customer data can be transformed into actionable business insights through data cleaning, visualization, and customer behavior analysis.
It also highlights how data-driven segmentation can support proactive strategies to reduce customer churn and improve customer retention.
