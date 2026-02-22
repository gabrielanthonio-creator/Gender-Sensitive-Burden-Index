# GSBI Policy Dashboard — Nigeria Women's Nutritional Health Equity

## Overview

This is an interactive, single-file HTML policy dashboard presenting findings from the **Gender-Social Burden Index (GSBI)** research project on women's nutritional health equity in Nigeria. It is designed for policymakers, public health researchers, and government nutrition planning units.


## Project Details

| Field | Details |
|---|---|
| **Index** | Gender-Social Burden Index (GSBI) |
| **Focus** | Women's nutritional health equity across Nigerian regions |
| **Principal Investigator** | Oladimeji Anthonio Gabriel |
| **Institution** | University of Ibadan, Ibadan, Nigeria |
| **Funder** | Government of Japan via Global Development Network (GDN) |
| **Grant Amount** | $20,000 |
| **Collaborative Partners** | FERDI, CERDI, Tuvs |
| **Data Sources** | NDHS 2018, MICS 2021 |

---

## What the Dashboard Shows

The dashboard is organised into five thematic sections:

**1. Regional GSBI Scores**
Animated horizontal bar charts showing GSBI scores across Nigeria's six geopolitical zones (North-West through South-West), colour-coded by burden level (High / Moderate / Low).

**2. Rural vs. Urban Disparities**
A grouped bar chart comparing GSBI scores between rural and urban populations within each region.

**3. Education & Nutrition Outcomes**
A combined bar and line chart showing how GSBI scores, anaemia prevalence, and dietary diversity shift across four education levels (No Education → Higher Education).

**4. SHAP Feature Importance**
A ranked bar chart of the 12 strongest predictors of GSBI scores derived from machine learning (SHAP analysis), covering socioeconomic, nutrition, health, and environmental domains.

**5. Inequality Decomposition**
A doughnut chart breaking down the Theil Index into between-region (61.3%) and within-region (38.7%) inequality contributions.

---

## Key Findings

- North-West has the highest GSBI score (78.4); South-West the lowest (23.1) — a gap of over 55 points.
- Secondary education is the single strongest predictor of GSBI (SHAP value: 0.312) and causally reduces GSBI by 22.1 points (TMLE estimate).
- 4+ antenatal care (ANC) visits causally reduce GSBI by 11.4 points.
- Access to clean water causally reduces GSBI by 8.7 points.
- Decision-making autonomy reduces GSBI by 7.2 points, independent of wealth and education.
- 61.3% of total nutritional health inequality is explained by between-region differences.

---

## Policy Recommendations (Tabbed in Dashboard)

The dashboard includes a tabbed recommendations section covering three horizons:

- **Immediate Actions** — Scale GSBI to state-level MOH planning units; conditional cash transfers linked to ANC attendance.
- **Evidence-Based Interventions** — Girls' secondary education retention in northern states; mobile ANC units; integrated WASH-nutrition programming.
- **Structural / Long-Term** — Gender autonomy legislation; institutionalise GSBI within the Federal Ministry of Health (FMOH) monitoring framework via DHIS2.

---

## Technical Details

- **File type:** Single self-contained HTML file (no build step, no server required)
- **Dependencies (CDN-loaded):**
  - [Chart.js v4.4.1](https://www.chartjs.org/) — for all data visualisations
  - [Google Fonts](https://fonts.google.com/) — Playfair Display & DM Sans
- **Interactivity:** Animated bar charts on load; tabbed policy recommendations panel; responsive layout

---

## How to Use

1. Download `GSBI_Policy_Dashboard.html`.
2. Open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. No installation, server, or internet connection required beyond the initial CDN font/chart load.
4. To embed in a website, host the file on any static web server or platform (GitHub Pages, Netlify, etc.).

---

## Suggested Citation

> Gabriel, O.A. (2024). *GSBI Policy Dashboard: Nigeria Women's Nutritional Health Equity*. SRHIN/CEMPHER, Ibadan, Nigeria. Funded by the Government of Japan via GDN.

---

## Contact

For data access, collaboration, or policy enquiries, contact the Principal Investigator through SRHIN / CEMPHER, University of Ibadan, Nigeria.
