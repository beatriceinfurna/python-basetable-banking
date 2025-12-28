# Visualizations

This folder contains the main visual outputs generated during the exploratory and descriptive analysis phase of the project.

The figures included here support the findings discussed in the final report and are intended to provide an intuitive understanding of client behavior, transaction patterns, and key variables used to build the analytical base table.

All visualizations are based on synthetic banking data and were produced using Python (Matplotlib / Seaborn).

---

## Demographic Analysis

- **age_distribution_gender_1996.png**  
  Distribution of client ages in 1996, split by gender.  
  The plot highlights a strong overlap between male and female age distributions, with most clients concentrated between 20 and 60 years old.

---

## Transaction Behavior

- **txn_count_distribution_1996.png**  
  Distribution of the number of transactions per client in 1996.  
  This visualization shows high heterogeneity in client activity, with most clients clustered around a moderate transaction count and a smaller group of highly active clients.

- **transactions_over_time_1996.png**  
  Monthly number of transactions in 1996.  
  The plot reveals seasonal patterns, including lower activity during mid-year months and peaks at the beginning and end of the year.

- **incoming_vs_outgoing_1996.png**  
  Scatter plot of total incoming versus outgoing transaction amounts per client in 1996.  
  A strong positive relationship is observed, indicating consistent financial behavior across clients.

---

## Account Balances

- **ending_balance_distribution_1996.png**  
  Distribution of ending account balances in 1996.  
  The figure shows a wide range of balances, including both positive and negative values, reflecting realistic banking conditions.

---

## Transaction Types and Operations

- **k_symbol_distribution_1996.png**  
  Distribution of transaction types (K-symbols) in 1996.  
  Certain transaction categories dominate client activity, highlighting differences in how accounts are used.

- **operation_type_percentage_1996.png**  
  Percentage of clients using each operation type in 1996.  
  This visualization shows that most clients rely heavily on standard operations such as card payments and account withdrawals.

---

## Cards and Loans Analysis

- **cards_issued_1996_vs_1997.png**  
  Comparison of the number of cards issued in 1996 versus 1997.  
  The figure highlights changes in card issuance between the two years.

- **loans_granted_1996_vs_1997.png**  
  Comparison of loans granted in 1996 and 1997.  
  A noticeable decrease in loans granted in 1997 is observed, as discussed in the report.

---

## Dependent Variables (1997)

- **dv_card_1997_distribution.png**  
  Distribution of the dependent variable indicating whether a card was issued in 1997.  
  The plot shows a strong class imbalance, with relatively few clients receiving a card.

- **dv_loan_1997_distribution.png**  
  Distribution of the dependent variable indicating whether a loan was granted in 1997.  
  This visualization highlights an even stronger imbalance, which is critical for future predictive modeling.

---

## Correlation Analysis

- **correlation_heatmap.png**  
  Correlation heatmap of the main numerical variables in the analytical base table.  
  The heatmap identifies strong relationships between transaction volumes, balances, and account activity, supporting feature selection decisions.

---

These visualizations collectively provide a comprehensive overview of the dataset and form the empirical basis for the conclusions presented in the final report.

