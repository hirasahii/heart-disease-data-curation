# Heart Disease Data Curation and Analysis Pipeline

This repository contains an end-to-end health data science pipeline using
the UCI Cleveland Heart Disease dataset.

---

## Project Overview

The project demonstrates a reproducible health data workflow focused on
data curation, quality assessment, and responsible downstream analysis.

The workflow follows real-world practices commonly used in secure data
environments (SDEs/TREs) and applied health research.

---

## Dataset

- **Source:** UCI Cleveland Heart Disease Dataset
- **Domain:** Cardiovascular disease
- **Observations:** 300+ patients
- **Data type:** Structured clinical variables

Raw source files are preserved to maintain data provenance.

---

## Repository Structure

heart_disease_pipeline/ ├── data_raw/ │ ├── cleveland.data │ ├── processed.cleveland.data │ └── heart-disease.names │ ├── data_clean/ │ └── cleveland_analysis_ready.csv │ ├── 01_heart_disease_data_curation_pipeline.ipynb ├── 02_predictive_analysis.ipynb └── README.md

---

## Notebooks

### 01_heart_disease_data_curation_pipeline.ipynb

This notebook focuses on **data curation and preparation**:

- Loading and inspection of raw data
- Data quality checks and missingness assessment
- Explicit, documented cleaning decisions
- Outcome variable engineering
- Export of an analysis-ready dataset

This notebook represents the core data curation pipeline.

---

### 02_predictive_analysis.ipynb

This notebook demonstrates **downstream analytical use** of the curated data:

- Loading the analysis-ready dataset
- Selection of clinically relevant predictors
- Training a simple logistic regression model
- Interpretation of model coefficients
- Discussion of model limitations

The model is intended for demonstration only and is not optimised for
clinical use.

---

## Key Principles Demonstrated

- Transparent and reproducible data pipelines
- Separation of raw and processed data
- Explicit documentation of data quality decisions
- Responsible and interpretable modelling
- Health-data-focused analytical practice

---

## Disclaimer

This project is for educational and demonstrative purposes only.
The analyses and models presented are not intended for clinical
decision-making.

---

## Author

Hira Sahi  
