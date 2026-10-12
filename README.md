# 📊 India Data Analyst Job Market Analysis

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualisation-11557c?style=for-the-badge)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Viz-4c72b0?style=for-the-badge)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

---

## 📘 Introduction

An exploratory data analysis examining the **Data Analyst job market in India** to evaluate skill requisitions, hiring geography, and market compensation patterns.

---

## 🛠️ Background

This project investigates real-world Data Analyst job postings to answer:
1. What technical skills appear most frequently in job requisitions?
2. Which geographic regions in India concentrate the highest hiring density?
3. Which skills correlate with higher median pay?
4. What skills offer the optimal balance of market demand and compensation?

---

## 🧰 Tools Used

- **Language**: Python
- **Data Manipulation**: Pandas, NumPy, `ast`
- **Data Visualisation**: Matplotlib, Seaborn
- **Annotation Handling**: `adjustText`
- **Environment**: Jupyter Notebook, VS Code

---

## 📊 Analysis

---

## 📚 What I Learned

- **Tokenisation & List Unnesting**: Cleaned and exploded comma-separated and string-formatted skill lists into tidy tabular formats.
- **Relational Reshaping**: Engineered multi-index monthly pivot tables using `pivot_table(index='job_posted_month', columns='job_skills', aggfunc='size')` and normalized row proportions.
- **Visual Design**: Configured continuous palettes across Seaborn subplots, formatted currency/percentage ticks via `plt.FuncFormatter`, and applied automated text-repel routines using `adjustText`.
- **Domain Categorisation**: Structured and mapped tech tooling (`ast.literal_eval`) to segment programming languages, analyst tools, cloud services, and libraries.

---

## 🔎 Insights

- **Baseline Essentials**: SQL and Python lead demand volume by a wide margin, acting as core filters across enterprise listings.
- **BI Tool Parity**: Power BI and Tableau show comparable demand and appear alongside reporting workflows requiring Excel.
- **Specialisation Premium**: High median compensation shifts toward distributed data processing frameworks (Spark) and enterprise cloud ecosystems (Azure, AWS).
- **Hub Clustering**: Roles are concentrated in Tier-1 technical hubs (Bengaluru, Hyderabad, Pune, and NCR).

---

## 🏁 Conclusion

The data indicates that the optimal progression for a Data Analyst targeting the Indian job market is establishing core proficiency in **SQL** and **Python** for listing coverage, followed by specialized knowledge in **BI tooling (Power BI/Tableau)** and **cloud/big-data frameworks (Spark, AWS, Azure)** to access higher compensation brackets.

















