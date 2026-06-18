# Telecom Customer Churn Analysis with Power BI

## Project Overview

Customer retention is one of the most critical challenges in the telecommunications industry. This project analyzes customer churn patterns using a telecom customer dataset containing over 7,000 customer records.

The objective was to identify the key drivers of customer churn, quantify its financial impact, and provide actionable recommendations to improve customer retention.

The project combines:

- Data Cleaning & Wrangling
- Exploratory Data Analysis (EDA)
- Statistical Testing
- Design Thinking Methodology
- Interactive Power BI Dashboards
- Business Recommendations

---

## Dataset

Source: Maven Analytics Telecom Customer Churn Dataset
Link: https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics

### Dataset Summary

- 7,043 customer records
- 38 features
- Churn Rate: 26.5%

## Project Workflow

### 1. Data Cleaning & Preparation

Missing values were validated against business logic before treatment.

Examples:

- Missing internet-service fields were replaced where customers did not subscribe to internet services.
- Missing phone-service fields were handled based on service availability.
- Churn-related fields were preserved for churned customers only.

Tools Used:

- Python (Pandas)
- Power Query

### 2. Exploratory Data Analysis

The analysis focused on:

- Customer tenure
- Contract types
- Internet services
- Monthly charges
- Revenue contribution
- Customer demographics

Key Findings:

- Churned customers have significantly shorter tenure.
- Month-to-month contracts show the highest churn rates.
- Fiber optic customers experience the highest churn.
- Higher monthly charges are associated with greater churn risk.
- Customers with premium tech support and online security are less likely to churn.

---

### 3. Statistical Analysis

Methods used:

- T-Tests
- ANOVA
- Tukey HSD Tests
- Chi-Square Tests

Significant factors associated with churn:

- Contract Type
- Internet Type
- Offer Type
- Payment Method
- Marital Status
- Paperless Billing

---

### 4. Design Thinking Process

The project followed the Design Thinking framework:

1. Empathize
2. Define
3. Ideate
4. Prototype
5. Test

Stakeholder insights were gathered through interviews with professionals from PTCL (Pakistan Telecommunication Company Limited).

---

## Dashboard Sections

### Executive Overview
- Churn Rate
- Revenue at Risk
- Average Revenue
- Customer Status Distribution

### Customer Demographics I & II
- Churn by Age Group
- Churn by Marital Status
- Churn by Dependents
- Geographic Analysis

### Services & Subscriptions I & II
- Contract Type Analysis
- Internet Service Analysis
- Premium Service Adoption
- Offer Performance

### Revenue & Charges
- Revenue Loss Analysis
- Customer Lifetime Value
- Monthly Charge Distribution

### Churn Reasons
- Competitor Analysis
- Service Quality Issues
- Retention Offer Effectiveness

---

## Key Business Insights

- 26.5% of customers churned.
- Competitor-related reasons account for the largest share of churn.
- Month-to-month customers churn at significantly higher rates.
- Fiber optic customers represent a high-value but high-risk segment.
- Premium Tech Support and Online Security strongly improve retention.
- Revenue loss from churn exceeds $3.6 million.

---

## Recommendations

- Promote long-term contracts.
- Expand retention campaigns for high-risk customers.
- Offer Premium Tech Support and Online Security trials.
- Improve competitive pricing and service offerings.
- Focus retention efforts on customers in their first year.
- Incentivize referrals and automatic payment methods.

---

## Tools & Technologies

- Power BI
- Python
- Pandas
- Power Query
- Statistical Analysis
- Design Thinking

---

## Authors

- Zara Asim 29262
- Maryam Sultan 29186
- Hadiya Muneeb 28424
