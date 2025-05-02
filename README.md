**expense_audit**

Expense Audit Automation that detects anomalies in company expenses using pandas, scikit-learn, and pyod.

**Dependencies:**

pandas scikit-learn pyod matplotlib seaborn

**Input:**

**CSV file:** expenses.csv
**Columns:**  Date  Department  Category  Amount

**Pipeline:**

Cleans and encodes the dataset

Scales numeric features

Uses Isolation Forest to find outliers

Flags unusual expense entries

**Outputs:**

flagged_expenses.csv
Anomaly distribution plot (expense_anomalies_plot.png)
