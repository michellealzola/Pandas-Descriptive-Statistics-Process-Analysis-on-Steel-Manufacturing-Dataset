# 🧮 Pandas Descriptive Statistics & Process Analysis on Steel Manufacturing Dataset

**Author:** Michelle Alzola  
**Project Type:** Data Analysis & EDA (Exploratory Data Analysis)  
**Tools Used:** Python, Pandas  
**Dataset:** `ccm_rul_dataset.csv` (Continuous Casting Manufacturing)

---

## 📌 Overview

This repository contains a complete **problem set with solutions** using **Pandas** for descriptive statistics, correlation and covariance analysis, value counts, ranking, and rolling windows. The data comes from a real-world **steel manufacturing process**, making it ideal for **engineering applications**, **AI model prep**, and **process improvement analysis**.

---

## 🎯 Objectives

- Understand **data profiles and summary statistics** using Pandas
- Detect **process patterns, drifts, and anomalies**
- Use **rolling and expanding windows** to smooth data and detect trends
- Apply **group-based stats** to compare steel types, alloy methods, and crystallizer performance
- Identify how **chemical compositions** relate to outcomes like RUL (Remaining Useful Life)

---

## 📊 Key Analysis Topics

| Topic Section | Description |
|---------------|-------------|
| **Descriptive Statistics** | Mean, Median, Std, IQR, Range |
| **Value Counts & Membership** | Most common steel and alloy types |
| **Percent Change & Differences** | Detect production fluctuations |
| **Ranking & Sorting** | Identify top and bottom performers |
| **Correlation & Covariance** | Explore linear relationships between variables |
| **Missing Data Handling** | Count and manage NaNs across columns |
| **Rolling & Expanding Windows** | Smooth RUL and temperature for trend detection |
| **Group-Based Aggregations** | Compare RUL and alloy speed by type or unit |

---

## 🧠 Interpretations & Process Insights

- The steel weight and temperature distributions show **strong consistency**, reflecting process control.
- `RUL` values show **wide variability** — used to profile top-performing batches.
- High `C, %` and `Mn, %` levels could signal **specialty steel** or **process drift**.
- Most alloying is done via **open systems (99%)** → suitable for high-volume, low-spec steels.
- Sudden RUL drops in **May–June 2020** may suggest equipment or operational faults.
- Grouping by `steel_type` reveals which types perform best in terms of lifespan.

---

## 🔍 Why This Matters (Engineering/AI Context)

This exercise simulates **real-life industrial data exploration** and builds skills in:
- Creating **data pipelines** for predictive maintenance
- Understanding **failure patterns**
- Generating features for **AI-driven quality prediction**
- Profiling process parameters for **manufacturing optimization**

---
🚀 How to Run
Clone the repository:

git clone https://github.com/michellealzola/pandas_descriptive_statistics_rul_analysis.git
cd pandas_descriptive_statistics_rul_analysis
Install dependencies (optional but recommended):

pip install pandas numpy jupyter
Open in Jupyter:

jupyter notebook
📸 Featured Blog Post
Read the full blog post breakdown here:
🔗 Exploring Process Trends with Pandas: Manufacturing Insights

🔗 Related Tags
pandas data-analysis descriptive-statistics steel-manufacturing EDA RUL engineering-data correlation rolling-mean python

📬 Contact
For collaborations, feedback, or questions:
Michelle Alzola
🌐 www.python.michellealzoladesign.com

