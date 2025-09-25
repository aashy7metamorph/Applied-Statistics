# Applied-Statistics

# Sports and Finance Analytics 🚀

This repository contains two Jupyter Notebook projects that demonstrate how to apply statistical methods to real-world problems in **sports analytics** and **financial anomaly detection**.

---

## 📊 Project 1: Sports Analytics using Z-Score
- **Goal:** Select the best cricket players (batsmen, bowlers, and wicket-keeper) using performance metrics.  
- **Method:** Standardisation with **z-scores** to compare players across different statistics.  
- **Steps:**
  - Standardise batting and bowling features (e.g., Runs, Strike Rate, Wickets, Economy Rate).  
  - Invert negative metrics (e.g., Bowling Average, Economy Rate) so “lower is better” aligns with z-score direction.  
  - Sum z-scores to compute an overall performance score.  
  - Build the **Fantastic XI** team by selecting top players.  

**Notebook:** `sports_analytics.ipynb`

---

## 💰 Project 2: Anomaly Detection in Finance Transactions
- **Goal:** Identify unusual spending patterns in financial transactions.  
- **Method:** **Confidence Intervals** to set thresholds for normal vs. anomalous transactions.  
- **Steps:**
  - Compute overall mean, standard deviation, and 95% confidence interval of spending.  
  - Check if new transactions fall outside the confidence interval → flag as anomalies.  
  - Extend to **category-wise detection** (e.g., Groceries, Utilities) so anomalies can be caught in specific categories.  

**Notebook:** `confidence interval.ipynb`

---


