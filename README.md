# Candidate Application  
#### _Submission of Candidate Application for the role of Data Engineer at The Eviction Lab of Princeton University_
---
In order to apply to the Data Engineer role at the Eviction Lab, I am spinning up a concise data pipeline to meet the fourth criteria laid out in the listing. Please review the google collab script.

# Example DEV Level Data Pipeline: County-Level Evictions and Income Analysis (2010–2023)

This project demonstrates a beginner's level of proficiency with a handful of the tools mentioned in the JD. I use those tools to build a civic data pipeline of sorts, combining:

- **Legal Services Corporation eviction filings data (weekly county-level)**
- **U.S. Census Bureau ACS 5-Year data (multi-year, multi-variable)**
- Optional integration with **Zillow housing data**

Using Python, the Census API and hard copy of the Legal Services Corp, and DuckDB SQL in Google Colab, the project:

- Ingests, normalizes, and joins multiple sources of data  
- Aggregates eviction filings to annual levels  
- Enriches data with median income, poverty rate, and population  
- Outputs a clean dataset for analysis and visualization

The final product enables county-level comparison of eviction trends and economic hardship across all 50 U.S. states and D.C.
