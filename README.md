# Hospital_Analytics_Dashboard
SQL, Tableau


## Objective:
The goal of this project was to visualize and analyze a hospital’s patient encounter data using Tableau. The objective was to uncover yearly trends, encounter class distributions, procedure costs, and payer coverage patterns to support data-driven decision-making in hospital operations and healthcare cost management.

Tools Used:

- SQL: Data cleaning, filtering, and aggregation of large healthcare claims datasets.

- Tableau: Data visualization and dashboard creation for interactive analysis and reporting.

## Data Structure and Overview

## Process:

Data Preparation (SQL):

Queried and joined multiple tables containing cost, procedure, and patient data.

Calculated total and average out-of-pocket and payer coverage costs for each procedure.

Exported cleaned, summarized results for visualization.

Visualization & Insights (Tableau):

Created a side-by-side bar chart comparing out-of-pocket vs. payer coverage costs by procedure.

Applied sorting to rank procedures from highest to lowest average out-of-pocket cost.

Added KPI cards and legends to enhance interpretability.

Built an interactive dashboard to explore cost differences across procedures and patient types.

## Results:
[Hospital Analytics Dashboard](https://public.tableau.com/app/profile/sierra.brock/viz/Hospital_Analytics_Dashboard/Dashboard1?publish=yes)

## Key Insights:

### Encounters Overview

- Encounters increased steadily from 2011 to 2014, with a major spike in 2014 and another in 2021.

- The Ambulatory category consistently represented the largest share of encounters, peaking at 60.3% in 2014.

- Only 4.1% of encounters lasted more than 24 hours, suggesting most visits were short-term.

- Outpatient encounters notably rose in 2021 (40.2%), narrowing the gap with Ambulatory visits.

Dashboard Feature: Line charts and stacked bar visuals were used to show yearly encounter trends and category proportions with interactive tooltips.

### Cost & Coverage Insights

- Total claim costs peaked in 2011 and again in 2020, reflecting potential operational or demand surges.

- Inpatient and Urgent Care encounters consistently had the highest total claim costs.

- Nearly 48.7% of all encounters had no payer coverage, representing a significant uninsured population.

Dashboard Feature: A dual-axis chart compared total claim cost trends with encounter volumes over time, color-coded by encounter class.


### Procedure Insights

Most Frequent Procedures:

- Assessment of health and social care needs

- Hospice care

- Depression screening

- Renal dialysis

- Medication reconciliation

Most Expensive Procedures:

- Admit to ICU — $206,260.40 (Avg.)

- Coronary artery bypass grafting — $47,085.89 (Avg.)

- Lumpectomy of breast — $29,353.00 (Avg.)

Dashboard Feature: A sortable bar chart showing procedures by frequency and average base cost, with hover-based details for medical descriptions.

### Payer Coverage & Out-of-Pocket Costs

- NO_INSURANCE patients had the highest out-of-pocket costs, followed by Anthem and Humana.

- Medicaid provided the highest total claim coverage ($6,205.22 avg.), followed by Blue Cross Blue Shield and Medicare.

Dashboard Feature: Highlight tables and bar charts display payer coverage comparisons and average claim costs interactively.

## Summary of Insights

- Encounters surged in 2014 and 2021, likely linked to external healthcare or policy changes.

- Ambulatory and Outpatient visits dominate patient activity, while Inpatient and Urgent Care drive the highest costs.

- Nearly half of encounters lack payer coverage, representing a major financial challenge for the hospital.

- Tableau’s dynamic visuals made it possible to connect cost patterns with encounter and payer trends in real time.

## Recommendations: 

- Operational Efficiency: Reduce inpatient costs by expanding outpatient services and preventive care programs.

- Financial Strategy: Address uninsured patient segments through financial assistance programs or partnerships.

- Policy Planning: Monitor yearly encounter spikes (e.g., 2014 and 2021) to optimize resource allocation and staffing.
