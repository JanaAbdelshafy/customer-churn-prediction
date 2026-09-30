# Performance Report — Customer Churn Prediction

## Executive summary
This report presents a predictive workflow for identifying subscribers with elevated
churn risk and translating model output into concrete retention actions.

### Key results
| Metric | Value |
|---|---|
| Dataset size | 3,200 subscribers |
| Historical churn rate | 20.6% |
| Test-set ROC-AUC | 0.667 |

The workflow uses a reproducible preprocessing pipeline, categorical encoding,
standardization, and logistic regression to produce a per-customer churn-risk score.

## Business recommendations
1. Score customers weekly rather than relying on a one-time churn report.
2. Combine churn risk with customer value before prioritizing retention spend.
3. Route support-related risk toward service recovery rather than automatic discounts.
4. Test retention interventions with controlled experiments.
5. Monitor precision/recall and business outcomes after deployment.

## Scope and next steps
The model here is built on a simulated dataset and is presented as a case study, not a
deployed production system. Moving to production would involve real historical
behavior data, leakage checks, ongoing monitoring, periodic retraining, and model
governance.
