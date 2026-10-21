
# Telco Customer Churn Analysis

**University of Rwanda**  
**Department:** Computer Engineering  
**Course:** Computing Intelligence and Applications  
**Assignment:** Lab 1  
**Registration Number:** 224004118

---

## 1. Project Overview

This project analyzes the Telco Customer Churn dataset using Python in a Kaggle Notebook. The main objective is to understand customer churn through data preprocessing and exploratory data analysis (EDA).

The analysis examines how customer demographics, phone services, contract types, paperless billing, and payment methods relate to customer churn.

## 2. Dataset

**Dataset:** Telco Customer Churn  
**Source:** [Kaggle – Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The original dataset contains 7,043 customer records and 21 attributes.

The `Churn` attribute indicates whether a customer left the company:

- `0` – Customer stayed (No)
- `1` – Customer churned (Yes)

## 3. Tools and Libraries

- Python – Programming language
- Kaggle Notebook – Development environment
- Pandas – Data loading, preprocessing, and analysis
- Matplotlib – Data visualization
- Seaborn – Statistical data visualization

## 4. Methodology

### 4.1 Data Loading

The dataset was loaded into a Pandas DataFrame. The first and last five records were displayed to examine its structure.

### 4.2 Data Preprocessing

1. Converted the Churn attribute from Yes/No to 1/0.
2. Examined the data types of all attributes.
3. Converted TotalCharges from object to float64.
4. Identified 11 missing values in TotalCharges.
5. Removed records containing missing values.

After preprocessing, **7,032 customer records** remained, with no missing values.

### 4.3 Exploratory Data Analysis

**Demographic Analysis**
- Gender vs Churn
- SeniorCitizen vs Churn
- Partner vs Churn
- Dependents vs Churn

**Service Analysis**
- PhoneService vs Churn

**Payment and Contract Analysis**
- Contract vs Churn
- PaperlessBilling vs Churn
- PaymentMethod vs Churn

Counts, churn rates, and visualizations were used to compare customer groups.

## 5. Key Findings

| Attribute | Finding |
|---|---|
| Gender | Female and male customers had similar churn rates of 26.96% and 26.20%. |
| SeniorCitizen | Senior citizens had a higher churn rate (41.68%) than non-senior citizens (23.65%). |
| Partner | Customers without partners had a higher churn rate (32.98%). |
| Dependents | Customers without dependents had a higher churn rate (31.28%). |
| PhoneService | Churn rates were relatively similar for customers with and without phone service. |
| Contract | Month-to-month customers had the highest churn rate (42.71%), while two-year contract customers had the lowest (2.85%). |
| PaperlessBilling | Customers using paperless billing had a higher churn rate (33.59%). |
| PaymentMethod | Electronic check users had the highest churn rate (45.29%). |

## 6. How to Run the Notebook

1. Download or clone this repository.
2. Open the .ipynb notebook in Kaggle or Jupyter Notebook.
3. Download the dataset from the Kaggle source linked above.
4. Update the CSV file path in the notebook if necessary.
5. Run the notebook cells in order.

## 7. Conclusion

The analysis identified several customer characteristics associated with churn. Contract type and payment method showed particularly large differences in churn rates, while gender and phone service showed relatively small differences.

These findings provide insights into customer behavior and can help identify customer groups that may benefit from retention strategies.

---

**Academic Project – Computing Intelligence and Applications | Lab 1**
