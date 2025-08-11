# Healthcare-data-analysis-capstone
Excel healthcare data analysis &amp; dashboard: data cleaning, visualization, actionable insights
# Healthcare Data Analysis and Insights

## Problem Statement
The healthcare industry generates vast amounts of data daily. This project analyzes a comprehensive healthcare dataset (medical exams, hospitalization details, customer profiles) to extract insights into patient health, medical histories, and healthcare costs. Our goal is to deliver actionable insights for healthcare stakeholders through rigorous data cleaning, transformation, exploration, and visualization.

## Project Steps & Objectives

### Data Cleaning
- Checked for and filled missing values in key columns (Month, Year, Smoker, Hospital Tier, City Tier, State ID).
- Standardized categorical and numerical entries.
- Addressed inconsistent values in “Heart Issues” and “Smoker” columns.

### Data Transformation
- Split composite fields (e.g., “Names”) into structured columns.
- Converted text-based metrics to meaningful numerical/categorical values.
- Categorized BMI and HbA1C into standard health status buckets.
- Merged and formatted date fields; calculated patient age as of 8-June-2023.
- Formatted charges as currency.

### Data Exploration & Analysis
- Merged all tables into a unified “Healthcare” sheet using Customer ID.
- Retained key columns for analysis.
- Created pivot tables for:
  - Distribution of cancer history among smokers/non-smokers.
  - Surgeries and HbA1C in transplant vs. non-transplant patients.
  - Charges by weight and diabetes status.
  - Charges by hospital tier and state.
  - Correlation of age with BMI, HbA1C, and charges.

### Visualization & Dashboard
- Interactive dashboard with:
  - Pie/donut charts (cancer history, smoker status)
  - Bar/column charts (charges by status/tier/state)
  - Line/scatter plots (age vs. BMI/HbA1C/charges)
  - Slicers for “Weight Status” and “Diabetes Status”

## Key Insights

- **Cancer Prevalence:** Cancer history is more common among smokers (X%) than non-smokers (Y%).
- **Transplants & Surgeries:** Patients with transplant history have a higher average number of major surgeries (X vs. Y) and HbA1C (A vs. B).
- **Weight & Charges:** Obese patients incur higher healthcare charges on average compared to those with normal weight.
- **Diabetes & Costs:** Diabetic patients have higher average charges than prediabetics and non-diabetics.
- **State & Hospital Tier:** Hospital Tier 1 in State X has the highest average charges, while Tier 3 hospitals in State Y are more cost-effective.
- **Age & Health Risks:** There is a positive correlation between age and both BMI and HbA1C, indicating older patients have greater risk factors.
- **Age & Charges:** Healthcare charges tend to increase with patient age, especially for those with higher BMI and HbA1C.

## How to Use This Repository

- **Open `data/healthcare_cleaned.xlsx`** for the cleaned, analysis-ready dataset.
- **Explore the Excel dashboard** for interactivity; use slicers for “Weight Status” and “Diabetes Status” to filter insights.

---

*Created as part of my Data Analytics Capstone Project.*
