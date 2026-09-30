# Customer Churn Prediction — Case Study

**Focus:** Churn-risk modeling and retention analysis for a subscription business
**Role:** End-to-end modeling, from EDA to a deployable risk-scoring workflow

## Business questions
- Which customer characteristics are associated with churn?
- Can the business generate a repeatable churn-risk score?
- How should customer-success teams act on the score?

## Deliverables
- [`ConnectPlus_Churn_Model.ipynb`](./ConnectPlus_Churn_Model.ipynb) — full modeling notebook
- [`data/subscription_customers.csv`](./data/subscription_customers.csv) — subscriber-level dataset
- [`CLIENT_REPORT.md`](./CLIENT_REPORT.md) — executive summary and recommendations

## Approach
EDA → train/test split → preprocessing pipeline → categorical encoding →
standardization → logistic regression → ROC-AUC evaluation → confusion matrix →
customer risk segmentation.
