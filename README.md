<img width="1310" height="739" alt="Capture d&#39;écran 2026-07-28 021331" src="https://github.com/user-attachments/assets/ec0e9e01-7b6c-4c85-b986-f3ff6c72370f" />
<img width="1329" height="737" alt="Capture d&#39;écran 2026-07-28 021320" src="https://github.com/user-attachments/assets/702c73c1-1bca-4a42-9694-35346292a2e1" />
# Healthcare Clinic CRISP-DM Power BI Project

End-to-end CRISP-DM project analyzing a healthcare clinic dataset — from business understanding to a fully interactive Power BI dashboard with a star-schema data model and DAX measures.

## Overview

This project applies the six phases of the **CRISP-DM methodology** to a synthetic healthcare clinic dataset covering 50 clinics, 500 doctors, 1,000 staff members, 20,000 patients, and 100,000 appointments (with associated payments, treatments, and prescriptions).

## Business Questions Answered

- How is appointment volume distributed across clinics?
- What is the total income per clinic, city, and state?
- How many staff and doctors are assigned to each clinic?
- How many distinct medical specialties are covered per clinic?
- How many patients registered each year (2024–2026)?
- What is the most preferred payment method across clinics?
- What proportion of payments are made via insurance?
- What is the status of treatments (completed / ongoing / pending)?

## Data Model

A star schema with a snowflake branch (doctors/staff → clinics):

**Fact tables:** Appointments, Payments, Treatments
**Dimension tables:** Patients, Doctors, Staff, Clinics, Date

## Tech Stack

- **Power Query** — data cleaning and transformation (locale-safe date/number formatting, PII removal, deduplication checks)
- **Power BI Desktop** — data modeling, relationships, DAX measures
- **DAX** — 19 measures covering counts, sums, and ratios across all business questions

## Repository Contents

- `data/raw/` — original source files (CSV + TXT)
- `powerbi/` — Power BI project file (.pbix) with Power Query transformations, data model, DAX measures, and dashboards
- `docs/` — Business Understanding, Data Model diagram, and full CRISP-DM documentation
- `exports/` — PDF export of the final dashboard[Documentation_Projet_CRISP-DM.pdf](https://github.com/user-attachments/files/30440008/Documentation_Projet_CRISP-DM.pdf)




**Malak Azzouz** — [github.com/malakazz18](https://github.com/malakazz18)[Documentation_Projet_CRISP-DM.pdf](https://github.com/user-attachments/files/30439800/Documentation_Projet_CRISP-DM.pdf)
