# 🏥 Medicaid & CHIP Telehealth Utilization Analysis Using CMS Open Data (2018–2022)

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightgrey?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-orange)](https://matplotlib.org/)
[![CMS](https://img.shields.io/badge/Dataset-CMS%20Open%20Data-blue)](https://data.cms.gov/)
[![Google Colab](https://img.shields.io/badge/Platform-Google%20Colab-F9AB00?logo=googlecolab)](https://colab.research.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OrOKgkDu-tHjrIl4pbxnSJ6BjknKwxdH?usp=sharing)

---

## 📊 Overview

This project analyzes longitudinal telehealth utilization trends across Medicaid and CHIP populations in Pennsylvania and Ohio using publicly available CMS Medicaid datasets from 2018–2022.

The analysis uses the official **Telehealth Services Provided to the Medicaid and CHIP Population** dataset from Data.Medicaid.gov, containing monthly telehealth utilization metrics across U.S. state Medicaid systems.

This project examines how telehealth adoption evolved before, during, and after the COVID-19 pandemic, highlighting differences in healthcare access patterns, utilization behavior, and state-level adoption trends.

This project was completed during the TruBridge Healthcare Data Analytics Externship.

---

## 🧩 Key Steps

### 🧮 1. Data Preparation & Standardization

* Built and standardized a 12,700-row longitudinal CMS telehealth dataset
* Cleaned and harmonized multi-year healthcare utilization records
* Standardized variable formatting and yearly reporting structures
* Processed missing values and inconsistent categorical fields

### 🐍 2. Exploratory Data Analysis (Python)

* Analyzed telehealth utilization trends from 2018–2022
* Compared Medicaid and CHIP adoption patterns across Pennsylvania and Ohio
* Identified utilization shifts during and after the COVID-19 pandemic
* Evaluated longitudinal healthcare access patterns

### 🎨 3. Data Visualization

Developed 21 healthcare analytics visualizations including:

* Telehealth utilization growth over time
* State-level adoption comparisons
* Medicaid vs CHIP utilization trends
* Post-pandemic telehealth retention patterns
* Longitudinal healthcare access visualizations

---

## 📈 Key Insights

* 📈 Telehealth utilization increased sharply during the COVID-19 pandemic across both states.
* 🏥 Pennsylvania and Ohio demonstrated different telehealth adoption and retention trajectories.
* 💻 Medicaid and CHIP populations showed distinct healthcare utilization behaviors over time.
* 📊 Post-pandemic telehealth usage remained significantly above pre-2020 baseline levels, suggesting long-term integration into healthcare delivery systems.

---

## ⚙️ Tech Stack

* **Languages:** Python
* **Libraries:** Pandas, NumPy, Matplotlib
* **Tools:** Google Colab
* **Dataset:** CMS Medicaid Open Data

---

## 📂 Repository Structure

```bash id="jv4mth"
📦 medicaid-chip-telehealth-analysis
 ┣ 📄 cms_telehealth_analysis.ipynb       # Main healthcare analytics notebook
 ┣ 📂 visuals/                            # Exported charts and visualizations
 ┣ 📂 data/
 ┃ ┣ 📂 raw/                              # Original CMS datasets
 ┃ ┗ 📂 cleaned/                          # Standardized analysis datasets
 ┣ 📜 LICENSE
 ┗ 📘 README.md
```

---

## 🚀 How to Run

### Open in Google Colab (Recommended)

Open the notebook directly in Google Colab:

https://colab.research.google.com/drive/1OrOKgkDu-tHjrIl4pbxnSJ6BjknKwxdH?usp=sharing

Run all notebook cells sequentially to reproduce:

* Data cleaning
* Longitudinal standardization
* Exploratory healthcare analysis
* Telehealth utilization visualizations

---

## 📊 Google Colab Environment

This project was developed and executed using Google Colab for:

* Cloud-based healthcare data analysis
* Longitudinal data processing
* Python data visualization
* Reproducible analytics workflows

---

## 📊 Project Deliverables

### 💻 Google Colab Notebook

Interactive notebook containing:

* Data cleaning
* Longitudinal standardization
* Exploratory healthcare data analysis
* Telehealth utilization visualizations

https://colab.research.google.com/drive/1OrOKgkDu-tHjrIl4pbxnSJ6BjknKwxdH?usp=sharing

---

### 📑 Interactive Presentation

Gamma presentation:

https://gamma.app/docs/From-Crisis-to-Continuity-How-Telehealth-Reshaped-Care-Access-ut4cuv75dxk3coi

---

### 📄 Supporting Analysis Artifact

https://claude.ai/public/artifacts/cc6d38bc-ea1d-4020-afc1-b63184e51cb2

---

### 🖥️ Project Slides

https://drive.google.com/file/d/1-eEETUnuNSIFgNqsnaoxM_D05e592QVV/view?usp=sharing

---

## 📦 Data Access

Primary dataset used in this analysis:

**Telehealth Services Provided to the Medicaid and CHIP Population**
https://data.medicaid.gov/dataset/651fa253-4dd4-4867-8725-2b5ae1dd5ce9

Dataset includes:

* Monthly telehealth utilization metrics
* Medicaid and CHIP beneficiary service counts
* Rates per 1,000 beneficiaries
* State-level healthcare utilization data
* Telehealth modality categories
* Data quality indicators

Data sourced from:

* T-MSIS Analytic Files (TAF)
* Centers for Medicare & Medicaid Services (CMS)

After downloading the dataset, place the CSV file in the `data/raw/` directory before running the notebook.

---

## 🧾 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

Healthcare utilization data sourced from CMS Medicaid Open Data:
https://data.medicaid.gov/

Project completed during the TruBridge Healthcare Data Analytics Externship at Extern.

Maintained and analyzed by Hana Gabrielle Bidon.
