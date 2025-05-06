# Loan Data Quality & Lineage Dashboard

This project simulates a real-world data management pipeline using Lending Club's loan dataset. It focuses on identifying data quality issues, tracking lineage from raw ingestion to reporting, and visualizing insights through Power BI. The goal is to demonstrate practical data governance skills relevant to roles in data quality, metadata management, and financial data analysis.

---

## 🧪 Key Features

- **Automated Data Quality Checks**
  - Detects missing, zero, and negative values
  - Validates business rules (e.g., FICO score ranges, income thresholds)
  - Outputs a structured CSV of violations

- **Data Lineage Visualization**
  - Simulates data transformation steps from raw → cleaned → validated → dashboard
  - Built using `networkx` and `matplotlib`

- **Reference Data Integration**
  - Grade definitions, term codes, and loan status mappings
  - Demonstrates metadata usage in validation and enrichment

- **Power BI Dashboard**
  - Visualizes income distribution, loan brackets, and data quality metrics
  - Includes slicers and aggregated insights for business users

---

## 🛠 Tech Stack

- **Python**: pandas, numpy, matplotlib, networkx
- **Power BI**: Dashboard development and data modeling
- **CSV / Excel**: Reference data and export handling

---

## Acknowledgments

  Lending Club Loan Dataset:
  https://www.kaggle.com/datasets/wordsforthewise/lending-club

  Built as a portfolio project to demonstrate data governance, quality control, and reporting.
