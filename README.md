# HR Analytics: Predicting Employee Attrition

## Overview
This project aims to predict employee attrition using machine learning, uncover key attrition drivers, and recommend strategic HR interventions.

## Dataset
- IBM HR Analytics Employee Attrition & Performance Dataset
- 1,470 employee records, 35+ features

## Objectives
- Predict which employees are likely to leave
- Understand which factors drive attrition
- Recommend actionable strategies for retention

## Key Libraries
- `pandas`, `plotly.express`
- `sklearn` (Logistic Regression, Random Forest, Metrics)

## Key Findings
- Overtime, Single status, and Sales/Lab Tech roles are top predictors.
- Attrition highest among age 26–33 and frequent travelers.
- Logistic Regression had the best tradeoff between accuracy and recall.

## Performance

| Model             | Accuracy | Recall (Attrition) | F1-score (Attrition) |
|------------------|----------|--------------------|----------------------|
| Logistic Regression | 86%      | 23%                | 0.35                 |
| Random Forest       | 83%      | 11%                | 0.17                 |

## Recommendations
- Reduce overtime to prevent burnout.
- Tailored retention for at-risk roles.
- Flexibility and growth for singles and young employees.


## Author
Edosomwan Mitchell 

