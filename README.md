# Hospital Readmissions Predictive Analytics and Strategy

## Project Overview

This project focuses on analyzing historical hospital readmission data to identify key factors contributing to unplanned 30-day readmissions and to develop data-driven, actionable recommendations for hospital stakeholders aimed at improving patient care quality and reducing financial penalties.

The analysis involved extensive Exploratory Data Analysis (EDA), advanced data wrangling (including imputation of missing values), and temporal trend analysis of readmission rates across various facilities and medical conditions.

## Key Findings & Insights

  Inverse Quality Relationship: Initial EDA revealed an inverse relationship between high quality scores and unplanned visit rates, suggesting that areas with higher reported quality may still face significant challenges in reducing readmissions.
  
  Top Readmission Measures: The primary drivers for readmissions identified in the dataset were related to Heart Attack, Chronic Obstructive Pulmonary Disease (COPD), and Heart Failure.
  
  Data Quality Challenge: Significant challenges in data preprocessing included converting non-standard string values ('Not Available') to numerical types and strategically handling missing data across crucial metrics like readmission rates and patient counts.

## Actionable Recommendations for Reducing Readmissions

The following strategic recommendations are based directly on the project's analytical findings, focusing on high-impact interventions.

  A. Targeted Patient Care & Medication Management
  
  Implement "Meds-to-Beds" Program: Mandate a standardized protocol where pharmacists or specialized technicians deliver and provide counseling for the patient’s first dose of discharge medications at the bedside before they leave. This directly addresses medication non-adherence, a major driver of readmission.
  
  Condition-Specific Discharge Planning: Since Heart Attack, COPD, and Heart Failure are top readmission measures, implement multi-modal discharge education (interactive video, hands-on demonstrations, and native language materials) specifically tailored to these high-risk conditions.
  
  B. Post-Discharge System Enhancements
  
  7-Day Post-Discharge Telehealth Check-in: Implement a mandatory follow-up call or video visit from a Nurse Practitioner within 72 hours of discharge for patients identified as "High-Risk." This is crucial for catching early complications.
  
  Root Cause Analysis (RCA) Loop: Institute a mandatory, immediate RCA review for every unplanned 30-day readmission involving the discharging team (physician, nurse, pharmacist) to identify and correct systemic gaps, such as poor handoffs or follow-up scheduling errors.

## Technical Project Details

Languages and Libraries

Language: Python

Core Libraries: pandas, matplotlib, seaborn

Environment: Jupyter Notebook (Hospital_readmissions.ipynb)

## Technical Steps Performed

1. Data Ingestion and Initial Cleaning: Loaded proprietary hospital readmission data and performed initial assessment of data types and missing values.

2. Missing Data Imputation: Converted non-standard string values to NaN and applied median imputation to maintain the integrity of key readmission rate metrics, preparing the data for model building.

3. Exploratory Data Analysis (EDA): Visualized distributions, temporal trends (Unplanned Visits Over Time), and correlated readmission rates with other hospital quality measures.

4. Feature Engineering (Temporal): Extracted and analyzed time-based features to assess monthly and quarterly readmission trends.

# Note:
Unplanned Hospital Visits: provider data. This data set includes provider data for the hospital return days (or excess days in acute care [EDAC]) measures, the unplanned readmissions measures, and measures of unplanned hospital visits after outpatient procedures. NOTICE: Data from the 1st and 2nd quarters of 2020 are not being reported due to the impact of the COVID-19 pandemic. For more information, please reference https://qualitynet.cms.gov/files/5fb838aef61c410025a64709?filename=2020-111-IP.pdf.


