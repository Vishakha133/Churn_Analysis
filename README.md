# Customer Churn Analysis 📊

A Python and SQL-based customer churn analysis project that explores customer behavior, subscription patterns, support interactions, revenue impact, and churn risk.

## 🔍 Project Overview

This project combines three datasets:

* **Customer** — customer demographics and basic information
* **Subscription** — subscription details, plans, charges, CLTV, churn score, and cancellation information
* **Support** — complaints, escalations, and CSAT scores

The datasets are cleaned, standardized, and merged into a single analytical dataset for further analysis.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLite
* SQL
* Google Colab

## 📌 Analysis Performed

* Data cleaning and standardization
* Missing-value handling
* SQL database exploration
* Customer/subscription/support data merging
* Churn flag creation
* Churn rate and retention analysis
* Churn by subscription/plan type
* Churn by state and gender
* Revenue at risk analysis
* CLTV lost analysis
* Average tenure and ARPU
* Complaint and escalation analysis
* CSAT vs churn correlation
* Churn risk segmentation
* Monthly churn trend
* Correlation heatmaps
* Pairplot analysis
* Pivot-table analysis

## 📈 Key Findings

| Metric                       |     Result |
| ---------------------------- | ---------: |
| Churn Rate                   |     28.57% |
| Retention Rate               |     71.43% |
| ARPU                         |      18.85 |
| Total Revenue                |     395.79 |
| Revenue at Risk              |      73.94 |
| CLTV Lost                    |      2,047 |
| Average Tenure               | 1,547 days |
| CSAT–Churn Correlation       |      -0.63 |
| Escalation–Churn Correlation |       0.77 |

These metrics are calculated directly in the analysis notebook.

## 📊 Visualizations

The project includes:

* Monthly churn trend
* Churn by plan type
* Churn by state
* Churn by gender
* Correlation heatmaps
* Pairplots
* Pivot-table analysis

## 💡 Business Focus

The analysis can help identify customers and segments associated with higher churn risk, understand the revenue impact of churn, and investigate potential relationships between customer support experience and churn.

The notebook also proposes investigating state-level churn, changes affecting basic-plan customers, competitor activity, and customers with medium/high churn risk.
