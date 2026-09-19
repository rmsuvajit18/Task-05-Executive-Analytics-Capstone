# Task 05 – Executive Analytics Capstone

## Overview

This project was completed as part of the **EdVyro Internship – Task 05: Executive Analytics Capstone**.

The objective of this task was to communicate analytical findings to a **nontechnical decision-maker without overstating certainty**.

The analysis combines customer churn information into a concise executive story covering churn patterns, customer tenure, support activity, revenue exposure, subscription type, business priorities, recommendations, and limitations.

## Objective

The project focuses on:

- Selecting five insights that materially affect a business decision.
- Quantifying the impact of those insights.
- Stating assumptions and limitations clearly.
- Creating a coherent narrative from the business problem to recommended action.

## Dataset

The Task 05 dataset contains:

- **15 customers**
- **11 columns**
- **0 missing values**
- **0 duplicate rows**

Key fields include:

- `CustomerID`
- `Gender`
- `Age`
- `TenureMonths`
- `SubscriptionType`
- `MonthlyCharges`
- `TotalCharges`
- `ContractType`
- `SupportTickets`
- `PaymentMethod`
- `Churn`

## Five Executive Insights

### 1. Overall Customer Churn

- **7 of 15 customers** churned.
- Observed sample churn rate: **46.67%**.

**Business implication:** Customer retention is an important issue in this sample.

**Limitation:** The dataset contains only 15 customers, so the result should be treated as a sample observation rather than a conclusion about the wider customer population.

### 2. Contract Type and Churn

- All **7 observed churned customers** are on **Month-to-Month** contracts.
- No churn was observed in the One Year or Two Year contract groups.

**Business implication:** Month-to-Month customers may warrant closer retention monitoring and proactive engagement.

**Limitation:** The observed pattern does not prove that contract type causes churn.

### 3. Tenure and Support Activity

| Metric | Churn = No | Churn = Yes |
|---|---:|---:|
| Average Tenure | 29.12 months | 7.00 months |
| Average Support Tickets | 1.00 | 4.29 |

**Business implication:** Early-tenure customers and customers with higher support activity may be important groups for further retention investigation.

**Limitation:** These are associations in the sample and do not prove that lower tenure or higher support-ticket activity causes churn.

### 4. Revenue Exposure

Among churned customers:

- **Monthly charges:** 409.93
- **Historical total charges:** 3,109.51

**Business implication:** Customer churn has a measurable recurring-revenue dimension in the sample.

**Limitation:** These figures describe only the 15-customer sample and are not a forecast of future revenue loss.

### 5. Subscription Type

| Subscription Type | Customers | Churned Customers |
|---|---:|---:|
| Basic | 7 | 5 |
| Pro | 4 | 2 |
| Enterprise | 4 | 0 |

Observed churn proportions are approximately:

- **Basic:** 71.43%
- **Pro:** 50.00%
- **Enterprise:** 0.00%

**Business implication:** Subscription-level differences can help guide further investigation into customer experience and value drivers.

**Limitation:** The subgroup sizes are very small, so percentage comparisons should be interpreted cautiously.

## Recommended Business Actions

1. **Strengthen early customer onboarding** to support customers during the first months of the relationship.
2. **Proactively engage Month-to-Month customers** as an area for closer retention monitoring.
3. **Review recurring support-ticket patterns** and investigate unresolved service issues.
4. **Consider recurring revenue exposure** when prioritizing retention outreach.
5. **Collect more customer data** before making broader strategic decisions.

## Executive Story

The analysis follows this decision-making flow:

**Business Problem → Evidence → Business Impact → Business Priorities → Recommended Actions → Limitations**

The purpose is to translate customer-level analysis into clear information for a nontechnical decision-maker while keeping conclusions proportional to the available evidence.

## Assumptions and Limitations

- The analysis uses a sample of only **15 customers**.
- Results represent **sample observations**, not the full customer population.
- Observed relationships do not establish causation.
- Small subgroup sizes make percentage comparisons unstable.
- Revenue exposure values are descriptive and are not forecasts.
- Additional customer data would be required to validate the findings at scale.

## Deliverables

- `Task_05_Executive_Analytics_Capstone.pdf` – Executive presentation PDF
- `Task_05_Executive_Analytics_Capstone.mp4` – Presentation recording
- `Task_05_Executive_Analytics_Capstone.ipynb` – Analysis notebook
- `customer_churn_sample.csv` – Task dataset
- **Dashboard Link** – Power BI dashboard used for the analysis

## Links

**Power BI Dashboard:**  
`[Add your published Power BI dashboard link here]`

**Presentation Recording:**  
`[Add your public/unlisted presentation recording link here]`

## Tools Used

- Python
- Pandas
- Matplotlib
- Google Colab
- Power BI
- GitHub

## Conclusion

This capstone translates customer churn analysis into an executive-level story by connecting measurable evidence with business implications and practical actions. The analysis also makes the limitations of the small sample explicit so that recommendations are interpreted as evidence-based starting points for further investigation rather than definitive causal conclusions.
