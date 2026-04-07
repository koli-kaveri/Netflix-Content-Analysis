A complete end-to-end machine learning + business analytics project analyzing Netflix’s content strategy from 2010–2025. Includes EDA, feature engineering, model building, and actionable business recommendations.
#  Netflix Content Strategy Analysis (2010–2025)
### 🎓 MSc Data Science Project - University Portfolio

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.8-orange)

---

## 📌 Project Objective

Analyze Netflix's movie catalog (2010–2025) to generate **actionable business insights** and 
build a **machine learning model** that predicts content quality — helping Netflix decide 
what type of content to invest in for better growth.

> **Core Question:** *"What type of content should Netflix invest in more for better growth?"*

---

## 📦 Dataset

| Property | Value |
|---|---|
| File | `netflix_movies_detailed_up_to_2025.csv` |
| Rows | 16,000 movies |
| Columns | 18 |
| Year Range | 2010–2025 |
| Source | Netflix / TMDB combined dataset |

**Key Columns:** title, director, cast, country, date_added, release_year, genres, language, 
popularity, vote_count, vote_average, budget, revenue

---

## ✅ Steps Completed

| Step | Description |
|---|---|
| 1 | Business Problem Definition |
| 2 | Data Collection & Column Analysis |
| 3 | Data Cleaning (nulls, duplicates, type conversion) |
| 4 | EDA — 11 Visualizations |
| 5 | Feature Engineering — 10 new features |
| 6 | ML Model — 3 algorithms trained & compared |
| 7 | Model Evaluation — Confusion Matrix, ROC, Feature Importance |
| 8 | Business Recommendations — 10 actionable insights |

---

## 🤖 ML Model Summary

- **Task:** Binary Classification — predict if a movie will be "High Rated" (vote_average ≥ 7.0)
- **Best Model:** Random Forest (200 trees)
- **Accuracy:** ~79% | **AUC:** 0.82
- **Top Feature:** `vote_count` (audience engagement volume)

---

## 💡 Top 3 Business Insights

1. **Korea & Japan are critically underinvested** — K-Drama has proven global viral potential; double exclusive studio deals
2. **India content gap** — 528 titles for 1.4B population; triple regional language investment  
3. **Thriller is fastest-growing** — 400%+ growth 2015–2022; prioritize psychological thriller originals

See [`insights.md`](insights.md) for all 10 insights + weak area analysis.

---

## 🛠️ Tech Stack

`Python 3.12` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `scikit-learn` · `Jupyter`

---

## 📁 Repository Structure

```
├── netflix_project.ipynb          # Main Jupyter Notebook (all 10 steps)
├── netflix_movies_detailed_up_to_2025.csv  # Dataset
├── insights.md                    # Business recommendations
├── README.md                      # This file
└── figures/
    ├── fig_eda_overview.png
    ├── fig_ml_results.png
    └── fig_deep_dive.png
```

---

*MSc Data Science Project | Complete Netflix Content Analysis Pipeline*
