# Bank Customer Churn Analysis

## Problem Statement
Customer churn is one of the most critical challenges facing retail banks today. 
Losing customers — especially high-value ones — directly impacts revenue and growth. 
This project analyses a dataset of 10,000 bank customers to identify the key factors 
driving churn, enabling targeted retention strategies.

## Dataset
- **Source:** Churn_Modelling.csv
- **Rows:** 10,000 customers
- **Columns:** 14 features including demographic, account, and behavioural data
- **Target Column:** Exited (1 = Churned, 0 = Stayed)

## Tools Used
- Python, Pandas, Seaborn, Matplotlib
- Jupyter Notebook

## Key Findings
| Factor | Finding |
|---|---|
| Churn Rate | 20.37% overall — dataset is imbalanced |
| Geography | Germany churns at 32.4% — highest of all regions |
| Gender | Female customers churn at 25.1% vs 16.5% for males |
| Activity | Inactive members churn at nearly double the rate of active members |
| Age | Churned customers concentrated in 40-60 age range |
| Balance | Mid-to-high balance customers churn most |

## Business Recommendations
| Factor | Recommendation |
|---|---|
| Geography | Investigate Germany-specific service or pricing issues |
| Gender | Design targeted retention campaigns for female customers |
| Activity | Trigger re-engagement campaigns for inactive accounts |
| Age | Offer tailored products for mid-age customers (40-60) |
| Balance | Priority retention for mid-to-high balance customers — most valuable segment |

## Project Structure
bank-customer-churn-analysis/
│
├── Bank_Customer_Churn_EDA.ipynb   # Main analysis notebook
└── Churn_Modelling.csv             # Dataset

## How to Run
1. Clone this repository
2. Open `Bank_Customer_Churn_EDA.ipynb` in Jupyter Notebook
3. Run all cells top to bottom
