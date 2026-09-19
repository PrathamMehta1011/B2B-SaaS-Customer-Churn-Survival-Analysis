# B2B SaaS Customer Churn & Survival Analysis

## Project Overview
This project develops an end-to-end predictive survival analysis framework designed to forecast client lifespans and identify at-risk enterprise accounts before they reach critical cancellation windows. 

While traditional churn models rely on static binary classification (churn vs. no churn), this framework uses time-to-event survival modeling to isolate the temporal risk factors and operational bottlenecks driving account attrition. The goal is to translate probabilistic risk curves into an actionable retention framework for Customer Success teams to protect recurring revenue streams (ARR) and optimize retention ROI.

---

## Dataset
* **Source:** RavenStack B2B SaaS dataset
* **Attributes:** Account tenure, usage volume, feature adoption metrics, support interactions, and contract parameters.

---

## Methodology & Modeling Pipeline
1. **Data Exploration & Preprocessing:**
   * Covariate extraction, data hygiene, and handling censored vs. event-observed customer records.
   * Feature transformation and alignment for time-to-event survival estimators.
2. **Survival Modeling Framework:**
   * **Cox Proportional Hazards:** Evaluated hazard ratios across covariates to identify baseline risk drivers.
   * **Random Survival Forests (RSF):** Modeled non-linear relationships and high-order feature interactions across multi-tiered enterprise accounts.
3. **Deep Learning Integration:**
   * **DeepSurv:** Implemented a deep feed-forward neural network architecture acting as a Cox proportional hazards estimator to capture complex behavioral risk patterns.

---

## Key Business Insights & Strategic Impact
* **Proactive Account Tiering:** Replaced reactive post-cancellation outreach with a time-based early warning system, grouping accounts by survival probability curves.
* **Targeted Interventions:** Identifies high-risk accounts weeks prior to renewal milestones, allowing Customer Success teams to deploy localized engagement playbooks.
* **Commercial ROI:** Demonstrates how data-driven retention directly minimizes customer acquisition churn drag and shields annual recurring revenue.

---

## Tech Stack
* **Language:** Python
* **Data Processing & Analysis:** Pandas, NumPy
* **Machine Learning & Survival Analysis:** Scikit-learn, Scikit-survival, Lifelines
* **Deep Learning:** PyTorch
* **Visualization:** Matplotlib, Seaborn

---
