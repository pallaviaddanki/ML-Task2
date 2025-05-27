# ML-Task2
This project performs detailed Exploratory Data Analysis (EDA) on a COVID-19 dataset (`carona.csv`) containing patient symptoms, test results, and demographic information. The goal is to identify data patterns, detect anomalies, and gain insights using visualization and statistics.

# 🧬 COVID-19 Patient Symptom Analysis – EDA Project

This repository contains an exploratory data analysis (EDA) project performed on a real-world COVID-19 dataset (`carona.csv`). The dataset captures key symptoms, demographics, and test results of individuals screened for coronavirus, offering a unique opportunity to uncover patterns related to infection risk and symptom trends.

---

## 🎯 Project Goal

The primary objective of this task (as part of the AI & ML Internship program) was to investigate the dataset, extract insights, and build a strong intuition about the relationships between symptoms and COVID-19 positivity using visual and statistical tools.

---

## 📂 Dataset Summary

- **File Name**: `carona.csv`
- **Rows**: 10,000+ suspected case records
- **Columns**: 
  - `Cough_symptoms`, `Fever`, `Sore_throat`, `Shortness_of_breath`, `Headache` – Symptom indicators (`TRUE`/`FALSE`)
  - `Age_60_above`, `Sex` – Demographic info
  - `Corona` – COVID-19 test result (`positive`/`negative`)
  - `Known_contact` – Contact-tracing related
  - `Test_date`, `Ind_ID` – Metadata

---

## 🛠️ Methods Used

- **Data Cleaning**: Handled missing values and standardization of categorical values.
- **Summary Statistics**: Explored frequency, distributions, and category counts.
- **Visualizations**:
  - Bar plots to show symptom distributions
  - Count plots segmented by gender and test results
  - Comparative visualizations for infected vs. non-infected individuals

---

## 📊 Key Takeaways

- Fever and cough were the most commonly reported symptoms among both positive and negative patients.
- A noticeable imbalance in gender and age reporting exists.
- Many cases lacked contact-tracing data (`Known_contact = None`), highlighting real-world data collection challenges.
- Strong class imbalance in `Corona` results — most individuals tested negative.

---

## 🔧 Tools & Libraries

| Tool        | Purpose                      |
|-------------|------------------------------|
| Python      | Programming Language         |
| Pandas      | Data loading and analysis    |
| Matplotlib  | Plotting basic graphs        |
| Seaborn     | Advanced statistical plots   |
| JupyterLab  | Interactive development      |

---

## 📁 Repository Contents

```bash
📦 carona-eda/
├── carona.csv             # Dataset file
├── carona_eda.ipynb       # Jupyter notebook with full EDA
├── README.md              # This file
└── screenshots/           # (Optional) Charts and graphs
