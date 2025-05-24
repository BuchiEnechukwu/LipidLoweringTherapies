# Identifying Gaps in Lipid-Lowering Therapy Uptake in North West London

The task involved using **CVDPREVENT open data** to identify patients in NWL who may be eligible for **lipid-lowering therapy (LLT)** but are not currently on treatment, with a focus on both primary and secondary prevention. The work also includes forecasting trends and identifying potential inequalities in treatment uptake.



## Task Objectives

This analysis addresses the following:

-  **How many patients with existing CVD (secondary prevention) are not on LLT?**
-  **How many high-risk patients (primary prevention) are not on LLT?**
-  **Are there disparities in uptake across boroughs or population groups?**
-  **What are the trends since Sept 2021, and what can we predict for the next 1–2 years?**

The analysis informs targeted interventions for reducing cardiovascular risk and improving equity across North West London.



##  Data & Sources

- **Dataset:** NHS CVDPREVENT Data Extract (September 2021 – March 2024)
  - `CVDP009CHOL` – Treated with LLT (CVD, secondary prevention)
  - `CVDP008CHOL` – Treated with LLT (QRISK10, primary prevention)
- **Geography:** North West London Integrated Care System (borough-level)
- **Format:** Excel exports from NHS Digital



##  Methods Overview

- **Data Wrangling:** `readxl`, `dplyr`, `lubridate`, `janitor`
- **Exploratory Analysis:** Grouped and visualised LLT uptake across boroughs, risk groups, and time
- **Inequality Assessment:** Disaggregated by gender, borough, and QRISK score
- **Time Series Forecasting:** 
  - Created monthly time series objects (2021–2024)
  - Applied `auto.arima()` from the `forecast` package to predict LLT gaps up to 2026
  - Visualised predicted untreated high-risk populations



##  Repository Contents

| File | Description |
|------|-------------|
| `NWL_LLTreport.Rmd` | Full R Markdown report (analysis, visualisation, forecasting) |
| `CVDP009CHOL.xlsx` | Data extract – Secondary prevention |
| `CVDP008CHOL.xlsx` | Data extract – Primary prevention |
| `README.md` | Project overview and documentation |



##  Key Insights

- Thousands of high-risk patients remain untreated in both primary and secondary prevention categories.
- Borough-level differences in LLT uptake suggest geographic inequalities.
- Forecasts show the gap in treatment may persist or widen without targeted interventions by 2026.



##  Tools & Environment

- Language: **R**
- Key Libraries: `tidyverse`, `lubridate`, `forecast`, `tseries`, `janitor`, `ggplot2`



## Relevance
The findings inform public health and primary care strategies to close LLT gaps and improve secondary prevention in cardiovascular care, especially for high-risk and underserved populations.



## Author
Onyebuchi Enechukwu
[@BuchiEnechukwu](https://github.com/BuchiEnechukwu)  
Please contact via GitHub for questions or collaboration.
