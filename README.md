# Bank Customer Churn Prediction

Predict whether a bank customer will leave (churn) or stay by analyzing demographic and financial attributes. Churn directly impacts revenue and profitability; early identification enables targeted retention that improves satisfaction and reduces losses. This project applies machine learning to forecast churn so the bank can act proactively—especially for high-value customers.

---

## Dataset

- **Source:** Kaggle (10,000 rows × 14 columns).  
- **Unit of analysis:** One row per customer.  
- **Task:** Predict churn from demographic and financial features.

### Data Dictionary

| Column           | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| RowNumber        | Row index in the dataset                                                    |
| CustomerId       | Unique customer identifier                                                  |
| Surname          | Customer’s last name                                                        |
| CreditScore      | Customer’s credit score                                                     |
| Geography        | Customer’s country                                                          |
| Gender           | Customer’s gender                                                           |
| Age              | Customer’s age                                                              |
| Tenure           | Years with the bank                                                         |
| Balance          | Account balance                                                             |
| NumOfProducts    | Number of bank products used                                                |
| HasCrCard        | Credit card ownership (1 = yes, 0 = no)                                     |
| IsActiveMember   | Active member status (1 = yes, 0 = no)                                      |
| EstimatedSalary  | Estimated annual salary (USD)                                               |
| Exited           | Churn flag (1 = churned, 0 = retained)                                      |

**Predictors (independent variables):**  
Demographics (Age, Gender, Geography), Financial (CreditScore, Balance, EstimatedSalary), and Bank info (NumOfProducts, Tenure, IsActiveMember, HasCrCard)

**Target variable:**  
`Exited` — binary indicator of churn.

---

## Objective

Build an accurate model to identify customers likely to churn so the bank can prioritize retention efforts and boost long-term profitability.

---

## Approach

1. **Data Preprocessing** — Clean the dataset; handle missing or inconsistent values.  
2. **Exploratory Data Analysis (EDA)** — Examine relationships between features and churn to surface key drivers.  
3. **Feature Engineering** — Create or refine features to improve predictive power.  
4. **Modeling** — Train and compare Logistic Regression, Decision Trees, Random Forests, and Gradient Boosting.  
5. **Evaluation** — Assess with Accuracy, Precision, Recall, F1-score, and ROC-AUC.

---

## Conclusion

An accurate churn prediction model enables the bank to identify at-risk customers early and deploy targeted retention actions. The insights from this analysis guide smarter customer strategies, strengthen loyalty, and ultimately improve overall business performance.
