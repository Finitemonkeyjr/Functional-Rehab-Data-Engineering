# Functional Rehab Data Engineering

Data engineering pipeline for cleaning, matching, and grouping clinical rehabilitation outcomes exported from Qlik Sense.

## Project Summary
Developed to support analysis of >10,000 de-identified patient records, this pipeline maps free-text diagnoses to standardized categories using regex and string pattern logic. It automates merging of pre/post assessments and exports results in Excel format for compliance tracking and outcome reporting.

## Tools & Methods
- R: `tidyverse`, `readxl`, `writexl`, `stringr`
- Regex-based diagnosis mapping
- Data reshaping and merging
- Excel export automation

## Repository Contents
- `dx_grouping_script.R` – Maps raw text to diagnosis groups
- `merge_outcomes_script.R` – Matches pre/post visits for analysis

## Data Disclaimer
Due to patient privacy, raw data is not included. All scripts are designed to work with standard Qlik Sense exports.

## Key Outputs
- Grouped diagnosis tables
- Matched outcomes ready for statistical analysis
- Automated compliance reports
