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

## 📊 Overview

This project analyzes longitudinal telehealth utilization patterns across Medicaid and CHIP populations in Pennsylvania and Ohio using CMS Medicaid Open Data (2018–2022).

The goal is to understand how telehealth adoption evolved before, during, and after the COVID-19 pandemic, with a focus on:

* Healthcare access patterns
* Utilization behavior differences across populations
* State-level variation in telehealth adoption
* Post-pandemic retention of virtual care services

This project was completed as part of a Healthcare Data Analytics Externship with TruBridge (via Extern).

---

## 🧠 Analytical Framing

This project treats CMS telehealth data as a structured healthcare analytics system designed to support:

* Population-level utilization analysis
* Comparative state healthcare access evaluation
* Medicaid vs CHIP behavioral differences
* Longitudinal healthcare delivery trend tracking

The analysis emphasizes **metric consistency, reproducibility, and standardized healthcare reporting logic**.

---

## 🧩 Data Model

To support structured healthcare analysis, the dataset is organized conceptually into:

### 📌 Fact Table: Telehealth Utilization

* Monthly telehealth visit counts
* Utilization rates per 1,000 beneficiaries
* Service volume metrics

### 📌 Dimension Tables

* **State:** Pennsylvania, Ohio
* **Time:** Monthly and yearly periods (2018–2022)
* **Population:** Medicaid, CHIP
* **Service Type:** Telehealth service categories

This structure enables consistent aggregation across time, geography, and population groups.

---

## 📊 Metric Definitions

To ensure consistency across analysis, the following metrics were defined:

* **Telehealth Utilization Rate:** Visits per 1,000 Medicaid/CHIP beneficiaries
* **Adoption Trend:** Year-over-year change in telehealth volume
* **Service Distribution:** Proportion of telehealth usage by service category
* **Retention Pattern:** Sustained utilization compared to pre-pandemic baseline

These definitions support reproducible and comparable healthcare reporting.

---

## 🧮 Data Preparation & Standardization

* Cleaned and standardized a **12,700-row CMS telehealth dataset** using Python (Pandas)
* Resolved missing values, inconsistent formats, and multi-year schema variation
* Structured dataset into an analysis-ready format for longitudinal comparison
* Ensured consistency in healthcare reporting variables across states and years

---

## 🔄 Analytical Pipeline

The project follows a structured analytics workflow:

1. **Data Ingestion** – CMS Medicaid Open Data (2018–2022)
2. **Data Cleaning** – Missing values, formatting inconsistencies, schema alignment
3. **Data Transformation** – Aggregation by state, time, and population group
4. **Metric Construction** – Standardized healthcare utilization metrics
5. **Exploratory Analysis** – Trend and cohort comparisons
6. **Visualization & Insight Generation** – Communication of findings

---

## 📈 Exploratory Analysis

Key analyses include:

* Telehealth utilization trends over time (2018–2022)
* State-level comparison of adoption trajectories (PA vs OH)
* Medicaid vs CHIP utilization behavior differences
* COVID-19 impact on healthcare delivery patterns
* Post-pandemic stabilization of telehealth usage

---

## 🎨 Data Visualization

Developed **21 visualizations**, including:

* Time-series trends in telehealth adoption
* State-level utilization comparisons
* Medicaid vs CHIP service distribution
* Post-pandemic retention curves
* Longitudinal healthcare access patterns

These visualizations were used to communicate findings to technical and non-technical stakeholders.

---

## 📌 Key Insights

* Telehealth utilization increased sharply during the COVID-19 pandemic across both states.
* Pennsylvania and Ohio exhibited different adoption and retention trajectories.
* Medicaid and CHIP populations demonstrated distinct utilization behaviors over time.
* Telehealth usage remained above pre-2020 levels, indicating sustained integration into healthcare delivery systems.

---

## ⚙️ Tech Stack

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib
* **Environment:** Google Colab
* **Data Source:** CMS Medicaid & CHIP Open Data

---

## 📂 Repository Structure

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

## 🚀 How to Run

### Option 1: Google Colab (Recommended)

Open the notebook:

[https://colab.research.google.com/drive/1OrOKgkDu-tHjrIl4pbxnSJ6BjknKwxdH?usp=sharing](https://colab.research.google.com/drive/1OrOKgkDu-tHjrIl4pbxnSJ6BjknKwxdH?usp=sharing)

Run all cells to reproduce:

* Data cleaning pipeline
* Metric construction
* Analysis and visualizations

---

## 📊 Project Outputs

### 📓 Interactive Notebook

Full end-to-end healthcare analytics workflow in Python.

### 📊 Visual Analysis

21 visualizations covering utilization trends and disparities.

### 📈 Presentation

Narrative summary of healthcare access trends and post-pandemic shifts.

---

## 🧾 Healthcare Data Source

CMS Medicaid & CHIP Telehealth Dataset:
[https://data.cms.gov/dataset/651fa253-4dd4-4867-8725-2b5ae1dd5ce9](https://data.cms.gov/dataset/651fa253-4dd4-4867-8725-2b5ae1dd5ce9)

Includes:

* Monthly telehealth utilization metrics
* Medicaid & CHIP service counts
* State-level healthcare access data
* Telehealth modality categories

---

## 🙌 Acknowledgments

* CMS Medicaid Open Data
* TruBridge Healthcare Data Analytics Externship (Extern program)

---

## 🧠 Author

Maintained and analyzed by **Hana Gabrielle Bidon**

Focus: Healthcare Analytics | Behavioral Data | Data Systems | Science Communication
