# Tata Elxsi Business Performance Diagnosis
A quarterly financial performance analysis of Tata Elxsi using Python and Power BI to investigate revenue growth, EBITDA margin compression, cost trends, and potential management actions.

**Tools:** Python · Pandas · Power BI · Excel  
**Domain:** Financial Analytics · Business Intelligence · Performance Analysis

## 1. Project Overview

This project analyzes Tata Elxsi Ltd.'s quarterly financial performance to investigate a key business question:

**Why did profitability decline, and what actions could management take to improve margins?**

Using quarterly revenue, expense, EBITDA-related metrics, and cost ratios, the analysis examines historical margin compression, revenue and expense growth patterns, and the subsequent recovery.

The project combines Python-based data processing with an interactive Power BI dashboard and a management-oriented executive summary.

## 2. Business Objectives

- Analyze quarterly revenue and expense trends.
- Calculate and compare year-over-year growth rates.
- Examine EBITDA margin trends and changes over time.
- Investigate employee and material cost ratios relative to revenue.
- Identify potential drivers of margin pressure.
- Translate analytical findings into actionable management recommendations.

## 3. Technology Stack

- **Python:** Data processing and financial KPI calculations.
- **Pandas:** Data cleaning, transformation, and time-series analysis.
- **Power BI:** Interactive dashboard and performance visualization.
- **Jupyter Notebook:** Reproducible analytical workflow.
- **Excel/CSV:** Tabular data storage and validation.

## 4. Analytical Workflow

1. Loaded and inspected quarterly financial data.
2. Validated dates, duplicate records, missing values, and key financial fields.
3. Calculated year-over-year revenue and expense growth.
4. Examined EBITDA margin and cost ratios over time.
5. Built Power BI visualizations to compare financial performance.
6. Prepared an executive summary with recommendations and analytical limitations.

## 5. Key Findings

- The calculated margin declined from approximately 27.9% in September 2024 to 21.0% in September 2025.
- By September 2026, the margin had recovered to approximately 21.9%.
- September 2026 revenue was approximately ₹1,056 crore, with year-over-year revenue growth of 15.0%.
- Expense growth was approximately 13.7% year over year in September 2026, indicating improved cost-growth alignment.
- Employee cost ratios remained an important area for further investigation.

*Note: Financial figures and historical EBITDA definitions must be reconciled with official company disclosures before publication. Potential cost drivers are hypotheses, not confirmed root causes.*

## 6. Dashboard

The Power BI dashboard includes:

- Latest revenue
- Latest EBITDA
- Latest EBITDA margin
- Year-over-year revenue growth
- Revenue growth versus expense growth
- Employee and material cost ratios
- Quarterly EBITDA margin trend

See `reports/dashboard_preview.png` for a static preview, if included.

## 7. Recommendations

1. Monitor workforce utilization, employee cost ratios, and revenue per employee.
2. Review project-level profitability, pricing, delivery costs, and resource allocation.
3. Introduce margin alerts when expense growth exceeds revenue growth or profitability falls below management targets.

These actions should be validated using project-level financial, staffing, and operational data before implementation.

## 8. Repository Structure

```text
tata-elxsi-business-performance-diagnosis/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── processing.ipynb
├── data/
│   └── processed/
│       └── tata_elxsi_quarterly_kpis.csv
├── outputs/
│   └──powerbi/
│      └── Tata_Elxsi_Business_Performance_Diagnosis.pbix
└── reports/
    ├── executive_summary.pdf
    └── dashboard_preview.png
```

## 9. How to Reproduce the Analysis

1. Clone or download this repository.
2. Install the dependencies listed in `requirements.txt`.
3. Open `notebooks/processing.ipynb` in Jupyter Notebook or VS Code.
4. Update file paths if necessary and run the notebook cells in order.
5. Open the Power BI file, if included, and update the data source path when prompted.

## 10. Limitations

This analysis uses aggregate quarterly financial data. It can identify trends and potential areas of concern but cannot independently establish the cause of margin compression. Historical metric definitions, unusual financial items, and calculated values should be reconciled with official company disclosures.

## 11. Data Sources and Attribution

List the official Tata Elxsi investor-relations pages and quarterly financial disclosures used to construct or validate the dataset. Clearly identify any derived or manually prepared dataset.

## 12. Author

**Yashvardhan Pravin Ganage**

Data Analytics | Business Intelligence | Financial Performance Analysis
