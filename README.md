# Aarete Capstone Project – Healthcare Spending & Health Outcomes

## Overview
This project was developed in partnership with Aarete as part of our capstone experience. Our research investigates the relationship between state-level healthcare spending and key health outcomes, with a particular focus on regional disparities and indicators like death rates, obesity, and smoking prevalence. Our goal was to uncover meaningful insights that can guide more effective healthcare investment decisions across the U.S.

## Repository Structure

### 1. Presentation
Contains our final deliverables:
- PowerPoint deck used in our client presentation.
- Poster summarizing our project visually.

### 2. Process
Includes all project files used to build visualizations and run models:
- **Orange Data Mining Files**: Input CSVs used in the machine learning tool Orange to explore correlations and model relationships between variables.
- **Tableau Files**: Datasets and cleaned spreadsheets used to create dashboards and visual narratives.

### 3. Report
Includes our written executive summary, outlining:
- Key questions explored
- Methods used
- Insights discovered
- Recommendations proposed

## Data 

All datasets were collected from public sources including the CDC, KFF, and Data.gov. The data was cleaned and standardized to allow for accurate merging by **state** and **year**. Once unified, this master dataset enabled comprehensive cross-variable analysis.

### Key Files in data:

| File Name | Description | Tool Used |
|-----------|-------------|------------|
| `Cleaned(in).csv` | Primary dataset used in Orange. It includes healthcare spending, death rate, and selected health indicators for all U.S. states. | Orange Data Mining |
| `Southeast(in).csv` | A subset of the main dataset focused on Southeastern states. Used to investigate regional health disparities. | Orange Data Mining |
| `Leading Cause of Death Per State.xlsx` | Dataset detailing the top causes of death per state. Helped support our Tableau visualizations. | Tableau |
| `health indicators per state (1).xlsx` | Contains state-level data on obesity, smoking, and other health risk factors over multiple years. | Tableau |
| `Expenditure Growth vs Inflation.xlsx` | Compares healthcare expenditure growth with inflation over time to examine national trends. | Tableau |

## Tools & Methodology

- **Tableau**: Used for exploratory data analysis and building dynamic dashboards. Helped us visualize patterns, regional differences, and year-over-year changes.
- **Orange Data Mining**: Enabled correlation analysis, clustering, and predictive modeling. Provided statistical reinforcement for our findings from Tableau.

## Executive Summary

Our executive summary, located in the `Report/` folder, distills the entire project into a short, actionable document. It covers our research objectives, methodology, and the strategic implications of our findings.

---

Thank you for exploring our project. Feel free to reach out if you have any questions or would like to build on our work!
