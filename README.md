<div align="center">

# 🏥 Insurance Data Analysis

<img src="https://fundvizer.com/wp-content/uploads/2025/02/WhatsApp-Image-2025-02-26-at-11.36.48.jpeg" width="500,height = 1000" style="border-radius:10px;"/>

### 📊 Exploratory Data Analysis — Customer Demographics, Policy Preferences & Premium Behavior

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge&logo=python&logoColor=white)](https://seaborn.pydata.org)
[![Kaggle](https://img.shields.io/badge/Kaggle-20beff?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com)

</div>

---

## 📌 Overview

A comprehensive **Exploratory Data Analysis** project on a health insurance dataset. The goal is to uncover patterns in customer demographics, policy behavior, and premium distribution through rigorous data cleaning and visualization — without applying machine learning models.

---

## 🎯 Objectives
```
01  Analyze customer distribution across city and region codes
02  Identify the most common insurance and policy types
03  Study the relationship between age range, policy duration, and premium
04  Understand how accommodation type affects spouse and policy behavior
05  Generate meaningful business insights using visualizations
```

---

## 📁 Project Structure
```
Insurance-Policy-Analysis/
│
├── notebook.ipynb          # Main analysis notebook
└── README.md               # Project documentation

```

---

## 📂 Dataset

| Column | Type | Description |
|--------|------|-------------|
| `ID` | int | Unique customer identifier |
| `City_Code` | str | Encoded city identifier |
| `Region_Code` | str | Encoded regional identifier |
| `Accomodation_Type` | str | Owned or Rented |
| `Reco_Insurance_Type` | str | Individual or Joint |
| `Upper_Age` | int | Upper age limit of insured |
| `Lower_Age` | int | Lower age limit of insured |
| `Is_Spouse` | bool | Policy includes spouse |
| `Health Indicator` | str | Customer health category |
| `Holding_Policy_Duration` | float | Years policy has been held |
| `Holding_Policy_Type` | str | Category of policy held |
| `Reco_Policy_Cat` | str | Recommended policy category |
| `Reco_Policy_Premium` | float | Recommended premium amount |
| `Response` | int | Target — accepted policy or not |

---

## 🔄 Analysis Pipeline
```
📥 Raw Data
   │
   ▼
🧹 Data Cleaning ──── Handle missing values, fix data types, remove outliers
   │
   ▼
🔍 Exploration ──────  Summary statistics, distributions, value counts
   │
   ▼
📊 Visualization ────  Bar, line, count, density, scatter, box plots
   │
   ▼
💡 Insights ─────────  Business conclusions and pattern discovery
```

---

## 💡 Key Insights

| # | Insight |
|---|---------|
| 01 | 🏙️ **City concentration** — C1 and C2 alone account for ~1,600 customers each, vastly outperforming all other cities |
| 02 | 👤 **Insurance preference** — Individual plans outnumber Joint plans at a 4:1 ratio |
| 03 | 💰 **Premium range** — Top 10 regions maintain average premiums between ₹34,000 and ₹40,000 |
| 04 | 🏠 **Accommodation & spouse** — Homeowners are 2x more likely to have a spouse than renters |
| 05 | 📉 **Long tail effect** — Most city codes (C30–C36) have fewer than 50 customers |

---

## 📈 Visualizations Used

| Plot Type | Purpose |
|-----------|---------|
| 📦 Box Plot | Outlier detection in numerical columns |
| 📊 Histogram | Distribution of budget and premium |
| 🔢 Count Plot | Categorical variable frequencies |
| 📉 Bar Plot | Regional and city-level comparisons |
| 📈 Line Plot | Policy duration vs premium trend |
| 🌊 KDE Plot | Density of recommended policy category |
| 🔵 Scatter Plot | Age range and premium relationships |

---

## ✅ Conclusion

This project demonstrates how **Exploratory Data Analysis** extracts actionable insights from raw insurance data. The cleaning pipeline and visual summaries provide a clear picture of customer demographics, policy trends, and premium behavior — forming a strong foundation for future predictive modeling.

---

## 👤 Author

<div align="center">

**Akisha Bhujel** — Data Analyst

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akisavujel)
[![Kaggle](https://img.shields.io/badge/Kaggle-20beff?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/akisavujel)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akishabhujel/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=firefox&logoColor=white)](https://akisavujel.github.io/Portfolio/)
[![Hashnode](https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)](https://hashnode.com/@akisavujel)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/akishabhujel/)

</div>

---

<div align="center">
<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExcnB0bnRicTMzd3NjYnpxamcyd2ljZjVwOHM4ZnEyMW5wNTAweW90MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9dg/69FiPmqxkmoy3KJUAw/giphy.gif" width="300"/>
</div>

---

<div align="center">
<sub>⭐ If this project helped you, consider giving it a star!</sub>
</div>
