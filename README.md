# 🏥 Healthcare Clinic Analytics — Power BI

> End-to-end healthcare analytics project following the CRISP-DM methodology, from data preparation and modeling to an interactive Power BI dashboard.

## 📊 Project Overview

This project analyzes a synthetic healthcare clinic dataset to explore operational, financial, staffing, patient, and treatment-related trends.

The project follows the **CRISP-DM methodology**:

```text
Business Understanding
        ↓
Data Understanding
        ↓
Data Preparation
        ↓
Data Modeling
        ↓
Analysis
        ↓
Visualization
```

## 📦 Dataset

The dataset contains approximately:

* 50 clinics
* 500 doctors
* 1,000 staff members
* 20,000 patients
* 100,000 appointments

The analysis covers appointments, payments, treatments, prescriptions, staffing, clinics, patients, and medical specialties.

## 🔎 Business Questions

The dashboard investigates:

* Appointment volume by clinic
* Revenue by clinic and location
* Patient registrations over time
* Staff and doctor distribution
* Medical specialties
* Payment methods
* Insurance usage
* Treatment status

## 🧩 Data Model

The project uses a **star-schema model**.

### Fact Tables

* Appointments
* Payments
* Treatments

### Dimension Tables

* Patients
* Doctors
* Staff
* Clinics
* Date

## 🛠️ Technology Stack

* Power BI Desktop
* Power Query
* DAX
* Data Modeling
* CRISP-DM

## 📐 DAX

The project contains **19 DAX measures** covering:

* Counts
* Sums
* Ratios
* KPIs
* Time-based analysis

## 🧹 Data Preparation

Power Query was used for:

* Data cleaning
* Data transformation
* Date/number formatting
* Duplicate checks
* PII removal
* Data preparation for modeling

## 📸 Dashboard Preview

Add 3–4 screenshots here.

```text
docs/
├── dashboard-overview.png
├── clinic-analysis.png
├── patient-analysis.png
└── financial-analysis.png
```

## 📁 Repository Structure

```text
├── data/
│   └── raw/
├── docs/
├── exports/
├── powerbi/
│   └── clinic.pbix
└── README.md
```

## 🎓 What I Learned

* Applying CRISP-DM to an end-to-end analytics project
* Data cleaning with Power Query
* Designing a star schema
* Writing DAX measures
* Building interactive dashboards
* Translating data into business questions and KPIs

## 🔮 Future Improvements

* Add automated data refresh
* Add predictive analytics
* Add patient-volume forecasting
* Add anomaly detection
* Connect the dashboard to a live database

- `exports/` — PDF export of the final dashboard[Documentation_Projet_CRISP-DM.pdf](https://github.com/user-attachments/files/30440008/Documentation_Projet_CRISP-DM.pdf)

<img width="1310" height="739" alt="Capture d&#39;écran 2026-07-28 021331" src="https://github.com/user-attachments/assets/ec0e9e01-7b6c-4c85-b986-f3ff6c72370f" />
<img width="1329" height="737" alt="Capture d&#39;écran 2026-07-28 021320" src="https://github.com/user-attachments/assets/702c73c1-1bca-4a42-9694-35346292a2e1" />


**Malak Azzouz** — [github.com/malakazz18](https://github.com/malakazz18)[Documentation_Projet_CRISP-DM.pdf](https://github.com/user-attachments/files/30439800/Documentation_Projet_CRISP-DM.pdf)
