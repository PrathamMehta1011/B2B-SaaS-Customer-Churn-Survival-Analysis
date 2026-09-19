# B2B-SaaS-Customer-Churn-Survival-Analysis
Project Overview
This repository contains an end-to-end predictive survival analysis framework designed to identify at-risk enterprise clients before they reach critical cancellation windows. Moving beyond traditional binary classification (churn vs. no churn), this project leverages time-to-event modeling to forecast individual customer lifespans, isolating the operational bottlenecks that drive account churn.

The primary objective is to translate complex probabilistic outputs into an actionable retention framework for Customer Success teams, enabling targeted interventions that protect Annual Recurring Revenue (ARR) and optimize Customer Acquisition Cost (CAC) ROI.

Dataset
Source: RavenStack B2B SaaS dataset

Features: Multi-tier account structures, usage metrics, contract parameters, and historical retention logs.

Methodology & Architecture
This project utilizes a multi-layered analytical pipeline to model non-linear risk factors and temporal churn patterns:

Exploratory Data Analysis (EDA) & Feature Engineering:

Covariate selection and data cleaning for survival modeling.

Identification of behavioral usage patterns and drop-off trends.

Predictive Survival Modeling:

Cox Proportional Hazards: Quantified baseline survival probabilities and feature impact.

Random Survival Forests: Captured complex, non-linear relationships across account tiers.

Deep Learning Integration:

DeepSurv: Deployed a Cox proportional hazards deep neural network to map nuanced behavioral risk factors across the enterprise client base.

Technology Stack
Language: Python

Data Processing: Pandas, NumPy

Machine Learning: Scikit-learn, Scikit-Survival

Deep Learning: PyTorch (DeepSurv implementation)

Visualization: Matplotlib, Seaborn

Business Impact & Strategic Value
Proactive Risk Management: Transitions retention strategies from reactive (post-cancellation notice) to proactive by tiering accounts based on their predicted survival curves.

Targeted Interventions: Enables Customer Success teams to deploy localized, data-driven outreach weeks before high-risk accounts renew.

Commercial ROI: Directly reduces churn rates to protect recurring revenue streams and improve overall customer lifetime value (CLV).
