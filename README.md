# West-Africa-Gas-Pipeline-Operational-Data-Analysis

# WAGPCo Operational Analysis

An independent operational analysis of the West African Gas Pipeline Company (WAGPCo), built entirely from public sources.

## Overview

WAGPCo operates the West African Gas Pipeline (WAGP), a 678 km cross-border natural gas pipeline connecting Nigeria, Benin, Togo, and Ghana. No API or structured dataset exists for this company. This project compiles and analyzes publicly available operational, financial, and structural data into a consistent, reviewable dataset.

## What's Included

- **Company profile**: ownership structure across six shareholders (Chevron, NNPC, Shell, Takoradi Power, Société Togolaise de Gaz, Société BenGaz)
- **Infrastructure specifications**: pipeline length, capacity, delivery points, water depth
- **Operational performance**: gas delivery volumes, asset availability, year-on-year growth
- **Country-by-country analysis**: role and trend data for Nigeria, Ghana, Togo, and Benin
- **Competitive positioning**: WAGP has no direct pipeline competitor; its real substitute is diesel and heavy fuel oil
- **Milestones and trends timeline**: 1982 to 2025
- **Gaps and opportunities**: stalled Ghana-Côte d'Ivoire expansion, potential landlocked country extension
- **A documented data gap**: WAGPCo's own public reporting discloses Nigeria's 68% supply share but never breaks out Ghana, Togo, and Benin's individual shares of downstream volume

## Files

| File | Description |
|---|---|
| `WAGPCo Data Analysis.ipynb` | Full Jupyter notebook with all code, tables, and charts |
| `wagpco_ownership.csv` | Shareholder structure |
| `wagpco_pipeline_specs.csv` | Infrastructure specifications |
| `wagpco_performance.csv` | Operational performance metrics |
| `wagpco_milestones.csv` | Historical milestones |
| `wagpco_substitute_fuels.csv` | Competitive/substitute fuel comparison |
| `wagpco_country_presence.csv` | Facilities by country |
| `wagpco_trends.csv` | Trends and expansion timeline |
| `wagpco_gaps_opportunities.csv` | Identified gaps and opportunities |
| `wagpco_country_trends.csv` | Country-specific volume and demand trends |
| `wagpco_additional_metrics.csv` | Cumulative volume, tax remittances, reverse flow, data gap notes |
| `*.png` | Supporting charts: ownership, timeline, country facility count, tax remittance |

## Methodology

All figures were sourced from public company statements, industry news reporting, and regulatory filings, current as of July 2026, then manually structured into a consistent dataset using Python and pandas. No figures were estimated or fabricated; where public data does not exist at the required level of detail, this is explicitly noted rather than filled in.

## Tools

Python, pandas, matplotlib, Jupyter Notebook

## Author

Courage Cobbinah
