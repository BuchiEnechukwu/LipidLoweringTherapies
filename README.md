## NWL LLT Report: Lipid Lowering Therapy Eligibility in North West London
This project investigates eligibility patterns for lipid lowering therapies (LLTs) in North West London using the CVDPREVENT audit dataset. It identifies population segments potentially missing out on preventive cardiovascular treatment and assesses uptake inequalities across demographic and clinical risk groups.

# Project Overview
•	Objective: To estimate the number of people eligible for LLT in North West London and identify potential gaps in access and treatment across demographic and risk groups.
•	Dataset: NHS England CVDPREVENT dataset (2021–2022)
•	Location: North West London (NWL) Integrated Care System
•	Main Deliverables: An automated R Markdown report, reproducible code, and visual summaries to support stakeholder decision-making.

# Methods
•	Language: R
•	Tools & Libraries: tidyverse, dplyr, readr, ggplot2, lubridate, knitr, rmarkdown
•	Data Processing:
•	Filtered and subsetted key indicators from the CVDPREVENT dataset.
•	Focused on indicators relating to:
•	Cardiovascular disease prevalence
•	QRISK10 and QRISK20 eligibility thresholds
•	Primary and secondary prevention metrics
•	Equity Analysis:
•	Stratified data by gender, practice group, and area deprivation.
•	Examined inequalities in LLT uptake across priority groups and treatment pathways.

# Outputs and Visualisations
•	Automated R Markdown Report:
•	Generates descriptive summaries and figures for use in presentations and publications.
•	Sample Visuals Include:
•	Bar plots of LLT eligibility by condition and risk group
•	Gender distribution of LLT uptake
•	Gap analyses between eligible and treated populations

# Key Insights
•	Significant eligibility–treatment gap among patients with high QRISK scores and those with established cardiovascular disease.
•	Gender and local authority-level variation in LLT coverage and adherence to clinical thresholds.
•	Potential system-level opportunities for improving targeted prescribing and reducing cardiovascular inequalities.

# Limitations
•	Dependent on completeness and quality of routinely collected audit data.
•	Limited by aggregated data structure (no individual-level patient data).
•	QRISK scores estimated based on grouped indicators rather than full risk profiles.

# Future Work
•	Integrate prescribing data to track LLT initiation over time.
•	Expand to cover intersectional inequalities (e.g., ethnicity, age, comorbidities).
•	Support co-design of local LLT improvement strategies with patients and clinicians.

# Relevance
The findings inform public health and primary care strategies to close LLT gaps and improve secondary prevention in cardiovascular care—especially for high-risk and underserved populations.

# Author
Onyebuchi Enechukwu
