
## 💰 Project 2: Anomaly Detection in Finance Transactions
- **Goal:** Identify unusual spending patterns in financial transactions.  
- **Method:** **Confidence Intervals** to set thresholds for normal vs. anomalous transactions.  
- **Steps:**
  - Compute overall mean, standard deviation, and 95% confidence interval of spending.  
  - Check if new transactions fall outside the confidence interval → flag as anomalies.  
  - Extend to **category-wise detection** (e.g., Groceries, Utilities) so anomalies can be caught in specific categories.  

**Notebook:** `confidence interval.ipynb`

---
