# Customer Churn Analysis 📊

## Project Overview

This project focuses on analyzing customer churn behavior to identify the key factors that influence customer retention and customer loss.

The analysis uses customer demographic data, service usage information, contract details, and payment behavior to understand why customers leave and what strategies can improve retention.

The dataset contains 7043 customer records with 21 attributes including customer details, services, contract type, charges, and churn status. 

---

## Objective

The main objectives of this project are:

- Analyze customer churn patterns
- Identify important factors affecting customer retention
- Understand customer behavior based on services and contracts
- Generate business insights using data visualization
- Recommend strategies to reduce customer churn

---

## Dataset Information

The dataset contains:

- Customer demographics
- Customer tenure
- Internet and phone services
- Additional services
- Contract information
- Payment methods
- Monthly and total charges
- Churn status

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Data Cleaning & Preparation

Performed the following steps:

- Loaded dataset using Pandas
- Checked dataset structure and information
- Converted TotalCharges into numerical format
- Checked and handled missing values
- Converted SeniorCitizen values into readable categories
- Prepared data for exploratory analysis

---

# Exploratory Data Analysis (EDA)

## 1. Overall Customer Churn Analysis

Analyzed the distribution of customers who stayed and customers who left.

### Key Insight:

- Around **26.5% customers churned**
- Around **73.5% customers were retained**

This shows that customer retention is good, but churn is still a significant business challenge.

---

## 2. Customer Tenure Analysis

Analyzed the relationship between customer tenure and churn.

### Insights:

- Customers with shorter tenure have a higher churn probability.
- Long-term customers show stronger loyalty.
- New customers are more likely to leave.

### Business Recommendation:

Improve onboarding experience and provide early customer engagement programs.

---

## 3. Internet Service Analysis

Analyzed churn behavior across internet service categories.

### Insights:

- Fiber Optic customers show higher churn compared to DSL users.
- Possible reasons:
  - Pricing concerns
  - Service expectations
  - Customer satisfaction issues

### Recommendation:

Improve Fiber Optic service quality and customer support.

---

## 4. Additional Services Analysis

Analyzed services:

- Online Security
- Online Backup
- Device Protection
- Tech Support

### Insights:

- Customers without additional services show higher churn.
- Customers using support and protection services are more likely to stay.

### Recommendation:

Promote additional service packages to increase customer engagement.

---

## 5. Contract Analysis

Analyzed churn based on contract type.

### Insights:

- Month-to-month customers have the highest churn rate.
- One-year and two-year contract customers show better retention.

### Recommendation:

Encourage customers to choose longer contracts using:

- Discounts
- Loyalty benefits
- Upgrade offers

---

## 6. Payment Method Analysis

Analyzed customer churn based on payment methods.

### Insights:

- Certain payment methods show higher churn behavior.
- Customers using automatic payment methods show better retention.

### Recommendation:

Encourage convenient automatic payment options.

---

## 7. Senior Citizen Analysis

Analyzed churn behavior among senior customers.

### Insights:

- Senior customers show comparatively higher churn.
- Personalized support can improve retention.

---

# Visualizations Created

The project includes:

- Churn count plot
- Churn percentage pie chart
- Gender vs Churn analysis
- Senior citizen churn analysis
- Tenure distribution
- Service-wise churn comparison
- Payment method churn analysis

---

# Business Insights

Main churn drivers identified:

1. Short customer tenure
2. Month-to-month contracts
3. Lack of additional services
4. Fiber Optic customer dissatisfaction
5. Payment behavior patterns

---

# Business Recommendations

To reduce churn:

- Improve new customer onboarding
- Provide loyalty programs
- Promote additional services
- Convert monthly customers into long-term contracts
- Identify high-risk customers early
- Improve customer support experience

---

# Project Structure

Customer-Churn-Analysis/

│
├── Customer_Churn.ipynb
├── Customer Churn.csv
├── Customer_Churn_Report.pdf
└── README.md
