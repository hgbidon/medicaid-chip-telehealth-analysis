# 🏥 Medicaid & CHIP Telehealth Utilization Analytics Pipeline (CMS Data, 2018–2022)

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-orange)](https://matplotlib.org/)
[![CMS Data](https://img.shields.io/badge/Data-CMS%20Medicaid%20Open%20Data-blue)](https://data.cms.gov/)
[![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=googlecolab)](https://colab.research.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OrOKgkDu-tHjrIl4pbxnSJ6BjknKwxdH?usp=sharing)

---

# 📊 Project Overview

This project analyzes longitudinal telehealth utilization patterns across Medicaid and CHIP populations in Pennsylvania and Ohio using CMS Medicaid Open Data from 2018–2022.

The analysis examines how telehealth adoption evolved before, during, and after the COVID-19 pandemic, with emphasis on:

* Healthcare access patterns
* Telehealth adoption and retention trends
* State-level utilization differences
* Medicaid vs CHIP behavioral variation
* Post-pandemic healthcare delivery changes

The project was completed as part of a Healthcare Data Analytics Externship with TruBridge through Extern.

---

# 🎯 Project Objectives

The primary goals of this analysis were to:

* Evaluate longitudinal telehealth utilization trends
* Compare adoption trajectories between Pennsylvania and Ohio
* Analyze utilization differences between Medicaid and CHIP populations
* Measure post-pandemic telehealth retention patterns
* Develop a reproducible healthcare analytics workflow using Python

---

# 🧠 Analytical Framing

This project approaches CMS telehealth data as a structured healthcare analytics system designed to support:

* Population-level utilization analysis
* Comparative healthcare access evaluation
* Longitudinal trend monitoring
* Standardized metric reporting
* Public health and operational insight generation

The analysis emphasizes reproducibility, metric consistency, and scalable reporting logic commonly used in healthcare analytics workflows.

---

# 🗂️ Data Model

To support structured analysis, the dataset was conceptually organized into fact and dimension tables.

## 📌 Fact Table: Telehealth Utilization

Contains:

* Monthly telehealth visit counts
* Utilization rates per 1,000 beneficiaries
* Service volume metrics

## 📌 Dimension Tables

### State

* Pennsylvania
* Ohio

### Time

* Monthly periods
* Yearly aggregation (2018–2022)

### Population

* Medicaid
* CHIP

### Service Type

* Telehealth service categories

This structure enables consistent aggregation across geography, time, and population groups.

---

# 📏 Metric Definitions

The following standardized metrics were used throughout the analysis:

| Metric                      | Definition                                              |
| --------------------------- | ------------------------------------------------------- |
| Telehealth Utilization Rate | Visits per 1,000 beneficiaries                          |
| Adoption Trend              | Year-over-year change in utilization volume             |
| Service Distribution        | Proportion of telehealth usage by service category      |
| Retention Pattern           | Sustained utilization relative to pre-pandemic baseline |

These metrics support reproducible healthcare reporting and comparative analysis.

---

# 🧹 Data Preparation & Standardization

The project included extensive healthcare data cleaning and transformation using Python and Pandas.

Key preparation steps included:

* Cleaning and standardizing a 12,700-row CMS telehealth dataset
* Resolving missing values and inconsistent formatting
* Aligning multi-year schema differences across datasets
* Standardizing reporting variables across states and populations
* Transforming raw CMS data into an analysis-ready structure

---

# 🔄 Analytics Pipeline

The project follows a structured end-to-end analytics workflow:

1. **Data Ingestion**
   CMS Medicaid & CHIP Open Data (2018–2022)

2. **Data Cleaning**
   Missing values, formatting inconsistencies, schema alignment

3. **Data Transformation**
   Aggregation by state, year, and population group

4. **Metric Construction**
   Standardized utilization and trend metrics

5. **Exploratory Analysis**
   Longitudinal and comparative healthcare analysis

6. **Visualization & Insight Generation**
   Communication of findings through visual analytics

---

# 📈 Exploratory Analysis

Key analyses include:

* Telehealth utilization trends over time
* COVID-19 impact on healthcare delivery patterns
* Medicaid vs CHIP utilization comparisons
* State-level adoption trajectory analysis
* Post-pandemic stabilization and retention trends

---

# 🎨 Data Visualization

Developed 21 visualizations to communicate utilization patterns and healthcare trends, including:

* Time-series telehealth adoption trends
* State-level utilization comparisons
* Medicaid vs CHIP service distribution
* Longitudinal retention curves
* Comparative healthcare access visualizations

---

# 📌 Key Findings

* Telehealth utilization increased sharply during the COVID-19 pandemic across both states.
* Pennsylvania and Ohio demonstrated different adoption and retention trajectories.
* Medicaid and CHIP populations exhibited distinct utilization behaviors over time.
* Telehealth usage remained above pre-2020 baseline levels, suggesting sustained integration into healthcare delivery systems.

---

# 🏥 Operational & Policy Relevance

This analysis demonstrates how longitudinal telehealth metrics can support:

* Medicaid program evaluation
* Healthcare access monitoring
* Population health reporting
* Post-pandemic care delivery assessment
* Public health and operational decision-making

---

# ⚙️ Tech Stack

## Languages

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib

## Environment

* Google Colab

## Data Source

* CMS Medicaid & CHIP Open Data

---

# 📂 Repository Structure

```bash
📦 medicaid-chip-telehealth-analysis
 ┣ 📄 cms_telehealth_analysis.ipynb
 ┣ 📂 data/
 ┃ ┣ 📂 raw/
 ┃ ┗ 📂 cleaned/
 ┣ 📂 visuals/
 ┣ 📜 LICENSE
 ┗ 📘 README.md
```

---

# 🚀 Running the Project

## Option 1: Google Colab (Recommended)

Open the notebook:

https://colab.research.google.com/drive/1OrOKgkDu-tHjrIl4pbxnSJ6BjknKwxdH?usp=sharing

Run all notebook cells to reproduce:

* Data cleaning pipeline
* Metric construction
* Exploratory analysis
* Visualizations and findings

---

# 📊 Project Deliverables

## 📓 Interactive Notebook

End-to-end healthcare analytics workflow in Python.

## 📊 Visual Analytics

21 visualizations illustrating utilization trends and comparative patterns.

## 📈 Presentation Materials

Narrative summary of healthcare access trends and post-pandemic telehealth adoption.

---

# 🧾 Data Source

CMS Medicaid & CHIP Telehealth Dataset:

https://data.cms.gov/dataset/651fa253-4dd4-4867-8725-2b5ae1dd5ce9

The dataset includes:

* Monthly telehealth utilization metrics
* Medicaid & CHIP service counts
* State-level healthcare access data
* Telehealth service categories

---

# 🔗 Additional Project Resources

## Interactive Artifact

https://claude.ai/public/artifacts/cc6d38bc-ea1d-4020-afc1-b63184e51cb2

## Presentation Deck

https://gamma.app/docs/From-Crisis-to-Continuity-How-Telehealth-Reshaped-Care-Access-ut4cuv75dxk3coi

## Project Presentation PDF

https://drive.google.com/file/d/1-eEETUnuNSIFgNqsnaoxM_D05e592QVV/view?usp=sharing

---

# 🙌 Acknowledgments

* CMS Medicaid Open Data
* TruBridge Healthcare Data Analytics Externship (Extern)

---

# 👩‍💻 Author

**Hana Gabrielle Bidon**

Healthcare Analytics | Behavioral Data | Data Systems | Science Communication
