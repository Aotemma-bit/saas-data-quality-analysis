\# SaaS Data Quality Analysis



\## Overview



This project analyzes a SaaS customer dataset using Python and pandas, with a focus on data quality, validation, cleaning decisions, and downstream analytical use.



The project was completed as part of the Tobi TS Academy Week 5 Pandas/Ingestion, Cleaning \& Slicing assessment.



\## Objectives



The analysis investigates:



\- Pandas Series alignment

\- Data-quality problems and their classifications

\- Duplicate records and repeated account IDs

\- Implied revenue per seat

\- Parsing versus validation of dates

\- Missing values and their different downstream consequences

\- How cleaning decisions depend on the analytical question



\## Tools



\- Python

\- Pandas

\- Jupyter Notebook



\## Key Data-Quality Issues Investigated



The dataset contains examples of:



\- Exact duplicate records

\- Repeated account IDs that represent different records

\- Missing values

\- Inconsistent country labels

\- Inconsistent plan capitalization

\- Zero values

\- Negative/special-coded MRR values

\- Invalid or ambiguous date representations

\- Dates that violate business logic

\- Extreme seat/MRR relationships



A key focus of the project is distinguishing genuine data-quality problems from unusual values that may be legitimate.



\## Repository Structure



```text

saas-data-quality-analysis/

├── notebooks/

│   └── saas\_data\_quality\_analysis.ipynb

└── README.md

