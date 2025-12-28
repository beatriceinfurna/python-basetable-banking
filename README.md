# Banking Basetable Construction — Python Data Engineering Project

## Project Overview
This individual project focuses on building a **client-level basetable** starting from
multiple relational banking tables.

The goal is to transform raw, normalized transactional data into a **single analytical table**
that can be used for business analysis, reporting, and predictive modeling.

The project emphasizes data engineering skills, business logic, and feature engineering
rather than model training.

---

## Business Context
Banks store information across multiple relational tables (clients, accounts, transactions,
loans, cards, etc.).  
To perform meaningful analysis or build predictive models, these tables must be consolidated
into a clean and well-defined basetable.

**Objective:**  
Create a reusable basetable at the **client level**, integrating information from all relevant
banking entities.

---

## Data Description
The project is based on **educational banking datasets** simulating real-world relational data.
The original data includes the following tables:

- `client`
- `account`
- `disp`
- `card`
- `loan`
- `order`
- `trans`
- `district`

Due to repository size considerations, only the **processed basetable** is included.
The raw tables follow a standard educational banking schema.

---

## Methodology
1. Analysis of table relationships and granularity  
2. Definition of the target entity (client-level)  
3. Data cleaning and standardization  
4. Feature engineering from transactional and account data  
5. Aggregation and joins across multiple tables  
6. Construction of the final basetable  

---

## Output
The final output of the project is a **client-level basetable**, stored in:
data/processed

This table is suitable for:
- Exploratory data analysis
- Business reporting
- Predictive modeling (e.g. churn, credit risk, cross-sell)

---

## Repository Structure
```text
python-basetable-banking/
├── data/
│   └── processed/          # Final client-level base table used for analysis
├── notebooks/
│   └── 01_basetable_creation.ipynb
├── report/
│   ├── final_report.pdf    # Final project report
│   └── visualizations/     # Figures generated during the analysis
└── README.md
```
---
## Tools & Technologies

- Python
- pandas
- numpy
- Jupyter Notebook

---

## Author
Individual academic project developed by Beatrice Infurna.

