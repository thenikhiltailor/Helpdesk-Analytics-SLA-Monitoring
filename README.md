# Automated IT Helpdesk & SLA Analytics Engine

An end-to-end data analytics and cleaning pipeline built in Python to audit, repair, and evaluate system-infrastructure operational metrics and Service Level Agreement (SLA) performance.

## 📊 Business Case & Operational Focus
Infrastructure downtime directly impacts commercial stability. This project simulates an enterprise IT environment—handling critical server metrics, managing missing data gaps safely, and engineering custom financial risk tracking indicators for leadership decision-making.

## 🛠️ Tech Stack & Core Operations
* **Data Pipelines & Structuring:** `Pandas` (DataFrame orchestration, conditional filtering, structural investigation)
* **Statistical Engineering:** `NumPy` (`np.nan` data marking, robust mathematical state management)
* **Visual Reporting:** `Seaborn` & `Matplotlib` (High-impact aggregation plots using a clean state-machine approach)

## ⚡ Key Architecture & Features
1. **Initial Structural Diagnostics:** Automates a data integrity scan using `.isnull().sum()` to pinpoint unrecorded metrics across distinct departments.
2. **Outlier-Resistant Imputation:** Implements a statistical **Median Imputation** strategy for system resolution hours to protect baseline SLAs from being corrupted by extreme infrastructure failure anomalies.
3. **Data Pruning:** Deploys target row isolation using `.dropna()` to strip out system logs missing critical impact scales.
4. **Feature Engineering (Risk Weight Index):** Calculates a custom commercial metric (Impact_Score_Times Sponsorship_Revenue_At_Risk) to give stakeholders instant clarity on technical threat levels.

## 📈 Dashboard Insights Included
* **Average SLA Technical Resolution Time:** An optimized Seaborn bar chart mapped explicitly by department.
* **Financial Risk Correlation:** A tailored Matplotlib scatter plot mapping incident severity directly against revenue exposure.
