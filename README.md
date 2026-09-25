# Healthcare Analysis for Doctor Visits_TIRTC

Exploratory Data Analysis (EDA) of the `DoctorVisits` dataset, examining patient demographics and healthcare utilization patterns to uncover trends in how often patients visit the doctor.

## 📌 Overview

This project performs an end-to-end exploratory analysis on doctor visit records, covering:

- Data loading and structural inspection (`head`, `tail`, `info`, `describe`)
- Missing value checks
- Univariate analysis of key variables (Gender, Age, Number of Visits)
- Bivariate analysis of doctor visits segmented by gender

The goal is to understand the distribution of patient attributes and identify whether visit frequency varies meaningfully across demographic groups such as gender.

## 📂 Dataset

- **File:** `DoctorVisits.csv`
- **Key columns used in this analysis:**
  - `gender` — patient gender
  - `age` — patient age
  - `visits` — number of doctor visits recorded

> Place `DoctorVisits.csv` in the project root before running the notebook.

## 🛠️ Tech Stack

- Python 3
- pandas — data loading and manipulation
- numpy — numerical operations
- matplotlib — plotting
- seaborn — statistical visualizations
- Jupyter Notebook

## 📊 Analysis Performed

| Step | Description |
|------|-------------|
| Data Overview | Preview rows, check data types, and summary statistics |
| Missing Value Check | `isnull().sum()` to confirm data completeness |
| Univariate: Gender | Count plot of gender distribution |
| Univariate: Age | Histogram + KDE of age distribution |
| Univariate: Visits | Count plot of number-of-visits distribution |
| Bivariate: Visits by Gender | Grouped aggregation (`count`, `mean`, `median`) and bar plot of average visits per gender |

