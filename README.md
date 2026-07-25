<h1 align="center">Kingsley Eboh</h1>
<h3 align="center">Data Analyst</h3>

<p align="center">
England &nbsp;|&nbsp;
<a href="mailto:kingsley.eboh49@gmail.com">kingsley.eboh49@gmail.com</a> &nbsp;|&nbsp;
<a href="https://linkedin.com/in/kingsleyeboh">linkedin.com/in/kingsleyeboh</a>
</p>
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=flat&logo=microsoftazure&logoColor=white"/>
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/XGBoost-FF6600?style=flat&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white"/>
</p>

---

## About Me

I am a data analyst with five years of experience working with complex datasets in environments where accuracy, governance and the reliability of analytical outputs directly affect the quality of decisions made. My work has involved large scale data analysis, data quality assessment, root cause investigation, governance documentation and explaining complex findings clearly to both technical and non-technical audiences.

I came to data analytics through years spent in regulated environments, where a single data error had direct consequences for real people, where audit readiness was not optional, and where the line between a finding and a conclusion was treated with real seriousness. I have carried that discipline forward into every analytical problem I have worked on since, regardless of domain.

The projects in this portfolio are self-directed and independently built, using Python, SQL, Power BI, cloud data platforms and machine learning on real world datasets. I built them to hold myself to the same standard I would expect in any professional setting, whether or not anyone was reviewing the work

---

## What Makes Me Different

I do not move forward with a finding until I have tested whether my conclusion actually follows from the evidence in front of me, rather than simply sounding plausible. I also think carefully about who will read the work and what they need from it, before I decide how to present it.

I think about the person at the end of every analysis, and the decision they are about to make because of it. That keeps me honest about what I can and cannot claim, deliberate about how I communicate uncertainty, and precise about the distinction between what the data shows and what I believe it means.

I hold myself to a standard of accuracy and follow through in every task I handle. I bring the same rigour to how I handle data itself. I am conscious of access boundaries, protective of data integrity throughout an analysis, and aware that behind every dataset are real people who trusted an organisation with their information.

I have worked through problems independently and contributed to teams where open collaboration produced stronger outcomes than either person could have reached alone. I know the difference between situations that call for input and situations that call for getting on with the work.

---

## Core Skills

**Data Analysis and Engineering**
Extracting, transforming and analysing large datasets using Python and
SQL. Building end to end analytical pipelines from raw data sources to
dashboard delivery. Identifying patterns, trends and anomalies in
complex multi-variable datasets across regulated and operational
environments.

**Cloud Data Pipelines and Forecasting**
Provisioning and connecting cloud data infrastructure on Microsoft
Azure, including Blob Storage, Data Factory and Azure SQL Database.
Building and backtesting time series forecasting models with Prophet,
validated against benchmark baselines before use. Making informed
engineering tradeoffs when tooling or connectors fail at scale, without
compromising the correctness or traceability of the underlying logic.

**Machine Learning and Predictive Analytics**
Building, tuning and evaluating classification models using scikit-learn
and XGBoost. Applying SHAP value analysis to produce transparent and
interpretable model explanations suitable for both technical and
non-technical audiences. Handling class imbalance, hyperparameter
optimisation and threshold tuning in business-relevant prediction
problems.

**Statistical Analysis and Signal Detection**
Applying statistical signal detection methods to identify anomalies
and elevated patterns in large datasets. Cross-validating findings
across Python and SQL to ensure analytical integrity. Presenting
findings with appropriate uncertainty and analytical hedging.

**Data Quality and Governance**
Assessing, validating and documenting data quality across complex
operational datasets. Maintaining audit ready processes and traceable
analytical outputs. Applying governance frameworks in regulated and
complex data environments.

**Data Visualisation and Reporting**
Building interactive Power BI dashboards designed and formatted for
presentation to senior and board level audiences. Producing publication
quality charts using matplotlib and seaborn. Writing analytical findings
in plain language accessible to non-technical stakeholders.

**Database and SQL**
Designing and querying relational databases in PostgreSQL and Azure SQL
Database. Writing analytical SQL including window functions, CTEs and
aggregations. Loading, transforming and validating data between Python,
cloud storage and SQL environments.

---

## Portfolio Projects


**Retail Demand Forecasting on Azure**

The business question: Can a validated forecasting model outperform naive seasonal planning enough to justify acting on a 90-day demand forecast, and where is the greatest inventory and seasonal risk sitting in the business?

4.5 million daily transaction records across 50 stores and multiple SKUs analysed on a full Azure cloud pipeline, Blob Storage, Data Factory and Azure SQL Database. Prophet forecasting model backtested against a naive baseline on a 90-day holdout across the five highest-volume SKU-store combinations. Delivered findings through a single decision-oriented Power BI dashboard connected directly to Azure SQL Database.

Outcome: Prophet reduced forecast error by roughly 50% against the naive baseline across every SKU-store combination tested, for example cutting MAPE from 19.3% to 10.7% on the highest-volume item. Identified a recurring seasonal revenue dip every September, holding in 4 of the last 5 years. Isolated five SKU-store combinations, all connected to a single high-demand item, carrying the highest stockout risk in the catalogue.

Transferable value: Cloud data pipeline architecture, time series forecasting, model validation and benchmarking, retail inventory analytics.
Stack: Python · Prophet · Azure Data Factory · Azure SQL Database · Azure Blob Storage · Power BI · pandas · scikit-learn

[View Project](https://github.com/Kingsley-Eboh/retail-demand-forecasting-azure)

---

**Bank Customer Churn Prediction**

The business question: Which retail banking customers are most likely
to close their accounts, and what factors are driving that decision?

10,000 customer records analysed across demographic, behavioural and
product usage dimensions. XGBoost model tuned to 86.6% ROC-AUC with
SHAP value analysis identifying Age, Number of Products and Member
Activity Status as the three strongest predictors of churn. Delivered
findings across 13 Python analyses, 12 SQL queries and a 3 page
Power BI dashboard.

Outcome: Germany recorded the highest churn rate at 32.4%, nearly
double France at 16.2%. Dormant accounts churned at 47.1%, more than
double the overall rate of 20.4%. Customers holding 3 or more products
churned at 82.7% and 100.0% respectively, signalling serious product
concentration risk. High value customers in Germany churned at 29.0%
with average balances exceeding £149,000. Model correctly predicted
churn for all top 20 highest risk customers in the test set with 100%
precision. Retaining just 20% of at-risk customers across all risk
tiers would preserve over £30 million in customer balances.

Transferable value: Predictive modelling, customer segmentation, churn
analysis, machine learning explainability, financial services analytics,
retention strategy support.

Stack: Python · XGBoost · scikit-learn · SHAP · PostgreSQL · Power BI ·
SQL · Jupyter · pandas

[View Project](https://github.com/Kingsley-Eboh/bank-churn-prediction)

---

**Clinical Trials Analysis**

The business question: What do 10 years of clinical trial registrations
reveal about pipeline efficiency, phase attrition and therapeutic area
trends across major pharmaceutical sponsors?

164,487 interventional trial records retrieved from the ClinicalTrials.gov
API covering January 2015 to December 2024, representing the complete
available population of trials meeting the search criteria. Delivered
findings across 13 Python analyses, 10 SQL queries and a 2 page
Power BI dashboard.

Outcome: Phase 2 to Phase 3 identified as the highest attrition point
in the pipeline at 54.8% transition rate. Oncology recorded the highest
termination rate at 17.7% and the highest overall attrition rate at
25.1%. Trial registrations peaked at 18,748 in 2021 and declined by
20.6% in 2024. Psychiatry and Mental Health identified as the second
largest therapeutic area with 11,147 trials and among the lowest
attrition rates, a significant and underinvested area of clinical
activity.

Transferable value: Life sciences analytics, pipeline analysis, sponsor
performance benchmarking, therapeutic area trending, regulatory data
engineering, API data retrieval.

Stack: Python · PostgreSQL · Power BI · SQL · Jupyter · pandas · REST API

[View Project](https://github.com/Kingsley-Eboh/clinical-trials-analysis)

---

**NHS Referral to Treatment: Performance Analysis**

The business question: Is the NHS meeting its 18-week constitutional
standard and where are the greatest performance pressures?

11 months of national RTT data covering 515 NHS trusts analysed across
23 treatment specialties. Delivered findings across 15 Python analyses,
10 SQL queries and a 2 page Power BI dashboard.

Outcome: NHS missed the 92% standard in every reporting period. Waiting
list reduced from 7.42 million to 7.16 million patients. Oral Surgery
identified as worst performing specialty at 51.5%.

Transferable value: Performance benchmarking, KPI monitoring, trend
analysis, operational reporting, large dataset handling.

Stack: Python · PostgreSQL · Power BI · SQL · Jupyter · pandas

[View Project](https://github.com/Kingsley-Eboh/nhs-rtt-analysis)

---

**NHS A&E: Emergency Care Analysis**

The business question: What is the scale of A&E performance failure
and how does winter pressure affect emergency care capacity?

Full year A&E data across 200 NHS providers analysed across 8 dimensions
including seasonal variation, provider benchmarking and regional
comparison.

Outcome: 26.9 million attendances recorded. 4-hour breach rate 39.4%,
nearly double the NHS target. 570,931 patients waited 12 or more hours
before being admitted to hospital.

Transferable value: Seasonal analysis, provider benchmarking, capacity
planning, operational performance reporting.

Stack: Python · PostgreSQL · Power BI · SQL · Jupyter · pandas ·
matplotlib · seaborn

[View Project](https://github.com/Kingsley-Eboh/nhs-trend-analysis)

---

**FDA Pharmacovigilance: Signal Detection Analysis**

The business question: Which drugs in the FDA adverse event database
carry the highest safety risk and what specific reactions are
statistically elevated?

6,000 adverse event reports retrieved via API across five pharmaceutical
products. Applied statistical signal detection methodology to identify
drug reaction combinations reported more frequently than expected by
chance. Delivered findings across 15 Python analyses, 15 SQL queries
and a 3 page Power BI dashboard.

Outcome: Identified Ibuprofen as carrying the highest mortality signal
at 20.50% death rate. Detected Drug withdrawal syndrome in Paracetamol
combination products at a signal strength of 777, meaning it was
reported 777 times more frequently than expected by chance. Confirmed
Metformin Lactic acidosis signal consistent with clinical literature.

Transferable value: Signal detection, anomaly identification, regulatory
data analysis, API data engineering, executive dashboard delivery.

Stack: Python · PostgreSQL · Power BI · SQL · Jupyter · REST API

[View Project](https://github.com/Kingsley-Eboh/fda-adverse-events-analysis)

---

**Enterprise Security Detection Lab**

The business question: Can enterprise authentication attacks be reliably
detected using Windows Security event logging?

This project demonstrates structured analytical thinking, audit log
analysis and pattern detection applied to security event data,
skills that transfer directly to any environment where data integrity,
access governance and anomaly identification matter.

Production-modelled Active Directory environment built on Windows Server
2022. Simulated brute-force, privilege escalation and authentication
abuse scenarios. Validated detection across 9 Windows Security event
captures.

Outcome: Successfully detected all simulated attack scenarios. Validated
detection coverage across authentication, privilege and process execution
event categories.

Transferable value: Audit log analysis, structured event data validation,
pattern detection in large log datasets, enterprise infrastructure
understanding, data security awareness.

Stack: Windows Server 2022 · Active Directory · PowerShell · VirtualBox

[View Project](https://github.com/Kingsley-Eboh/Enterprise-Active-Directory-Security-Lab)

---

## Certifications

- CompTIA Security+
- Google Cybersecurity Certificate
- AWS Cloud Practitioner Essentials · Amazon Web Services

---

## How I Work

I approach every analysis the same way regardless of domain or industry.

1. Start with the business question: What decision does this analysis
need to support?
2. Understand the data: Assess completeness, quality and limitations
before drawing conclusions.
3. Apply appropriate methodology: Match the analytical approach to the
question being asked.
4. Validate findings: Cross-check results across different tools and
approaches.
5. Communicate clearly: Present findings in language a non-technical
stakeholder can act on.

This workflow has been applied consistently across seven years of
professional analytical work and across every project in this portfolio.

---

## Currently Building

**A/B Testing and Causal Inference**
Applying experimentation and difference-in-differences methodology to
quantify the causal impact of interventions on business outcomes,
rather than relying on observational correlation alone.


