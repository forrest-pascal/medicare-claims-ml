# medicare-claims-ml

Healthcare machine learning research portfolio focused on predictive modeling using Medicare inpatient claims data for Major Joint Replacement or Reattachment of Lower Extremity (DRG 469/470).

---

# Research Overview

This research explored predictive modeling approaches using approximately 2.3 million Medicare inpatient claims records. The study focused on identifying predictors associated with readmissions, mortality, emergency department utilization, and healthcare risk outcomes using supervised machine learning techniques and healthcare analytics.

The research incorporated SAS Enterprise Miner, MATLAB, MLJAR, and Tableau to develop predictive models, evaluate algorithm performance, visualize healthcare trends, and analyze large-scale Medicare claims data.

---

# Technologies

- SAS
- SAS Enterprise Miner
- MATLAB
- Tableau
- MLJAR

---

# Research Areas

- Medicare Claims Analytics
- Predictive Modeling
- Healthcare Machine Learning
- Risk Stratification
- Readmissions Analytics
- Mortality Prediction
- Healthcare Utilization Analytics
- Feature Selection & Model Evaluation

---

# Model Evaluation & ROC Analysis

## Figure 9. Logistic Regression Results: ROC Curve

![Figure 9](visuals/roc_curves/figure9_logistic_regression_roc_curve.png)

---

# Feature Importance & Predictive Modeling

## Figure 14. NCA Feature Selection Analysis

![Figure 14](visuals/feature_importance/figure14_nca_feature_selection.png)

---

## Figure 18. Predictors Most Involved in Ensemble Boosted Trees Algorithm

![Figure 18](visuals/feature_importance/figure18_ensemble_boosted_trees.png)

---

## Figure 21. Predictors Most Involved in LightGBM Algorithm

![Figure 21](visuals/feature_importance/figure21_lightgbm_predictors.png)

---

## Figure 22. Predictors Most Involved in XGBoost Algorithm

![Figure 22](visuals/feature_importance/figure22_xgboost_predictors.png)

---

## Figure 23. Predictors Most Involved in Random Forest Algorithm

![Figure 23](visuals/feature_importance/figure23_random_forest_predictors.png)

---

# Healthcare Risk Visualizations

## Figure 6. Percentage of Beneficiary Claims with Questionable and Acceptable Risk

![Figure 6](charts/risk_visualizations/figure6_questionable_vs_acceptable_risk.png)

---

## Figure 25. Claims with Questionable Risk by State & Race

![Figure 25](charts/risk_visualizations/figure25_risk_by_state_race.png)

---

## Figure 34. Results for Type of Admission for novelrisk=0

![Figure 34](charts/risk_visualizations/figure34_type_of_admission_novelrisk0.png)

---

## Figure 35. Results for Type of Admission for novelrisk=1

![Figure 35](charts/risk_visualizations/figure35_type_of_admission_novelrisk1.png)

---

# Demographic & Population Analysis

## Table 14. Beneficiary Demographics

![Table 14](charts/demographic_analysis/table14_beneficiary_demographics.png)

---

## Figure 10. Prevalence of Comorbidities by Gender & DRG

![Figure 10](charts/demographic_analysis/figure10_comorbidities_gender_drg.png)

---

## Figure 11. Prevalence of Comorbidities by Race

![Figure 11](charts/demographic_analysis/figure11_comorbidities_race.png)

---

## Figure 12. Comorbidities by Count

![Figure 12](charts/demographic_analysis/figure12_comorbidities_count.png)

---

## Figure 13. Age, Race by Average Medicare Claim Payments within Gender

![Figure 13](charts/demographic_analysis/figure13_claim_payments_age_race_gender.png)

---

## Figure 26. Distribution of Race

![Figure 26](charts/demographic_analysis/figure26_distribution_race.png)

---

## Figure 27. Distribution of Novel Risk for race=unknown

![Figure 27](charts/demographic_analysis/figure27_novelrisk_unknown.png)

---

## Figure 28. Distribution of Novel Risk for race=White

![Figure 28](charts/demographic_analysis/figure28_novelrisk_white.png)

---

## Figure 29. Distribution of Novel Risk for race=Black

![Figure 29](charts/demographic_analysis/figure29_novelrisk_black.png)

---

## Figure 30. Distribution of Novel Risk for race=Other

![Figure 30](charts/demographic_analysis/figure30_novelrisk_other.png)

---

## Figure 31. Distribution of Novel Risk for race=Asian

![Figure 31](charts/demographic_analysis/figure31_novelrisk_asian.png)

---

## Figure 32. Distribution of Novel Risk for race=Hispanic

![Figure 32](charts/demographic_analysis/figure32_novelrisk_hispanic.png)

---

## Figure 33. Distribution of Novel Risk for race=North American Native

![Figure 33](charts/demographic_analysis/figure33_novelrisk_native.png)

---

# Dashboard Visualizations

## Tableau Dashboard Visualizations

![Dashboard](visuals/dashboards/tableau_dashboard.png)

---

# Dissertation Abstract

[Download Dissertation Abstract](abstract/dissertation_abstract.pdf)

---

# Demo Video

[Watch Presentation Video](demo/presentation_video.mp4)

---

# Key Findings

- Ensemble Boosted Trees demonstrated the strongest predictive performance across training and test datasets
- Physicians, providers, claim payment amounts, admission types, and beneficiary geography showed strong predictive importance
- Obesity and hypertension were among the most prevalent comorbidities
- White female beneficiaries represented the largest patient population and highest aggregate claim costs
- Machine learning models demonstrated strong potential for healthcare surveillance, utilization management, and risk stratification initiatives

---

# Repository Structure

```text
medicare-claims-ml/
│
├── abstract/
│   └── dissertation_abstract.pdf
│
├── charts/
│   ├── demographic_analysis/
│   └── risk_visualizations/
│
├── visuals/
│   ├── dashboards/
│   ├── feature_importance/
│   └── roc_curves/
│
├── demo/
│   └── presentation_video.mp4
│
└── docs/