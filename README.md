# 🏏 IPL Live Win Probability Predictor

Ball-by-ball **IPL 2nd innings win probability predictor** built using **Machine Learning (XGBoost)** and visualized in **Tableau**.

---

## 👨‍💻 Authors
- Om Naik
- Murali Manohara

---

## 📊 Project Overview

- **Dataset:** 1,169 IPL matches (2008–2025)
- **Records:** 278,000+ ball-by-ball deliveries
- **Problem Type:** Binary Classification (Win / Loss)
- **Best Model:** XGBoost (Highest Win Recall)

This project predicts **live win probability during the 2nd innings of an IPL match** using ball-by-ball match conditions.

---

## 🔧 Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Scikit-learn
  - XGBoost
- **Jupyter Notebook**
- **Tableau Public**

---

## 📈 Model Comparison

| Model | Accuracy | Win Recall | False Negatives |
|-------|----------|------------|-----------------|
| Logistic Regression | 78% | 0.68 | 4,291 |
| Random Forest | 75% | 0.69 | 4,242 |
| XGBoost | 77% | **0.72 ✅** | **3,765 (Best)** |

---

## 🔍 Key Findings

- **Pressure Index** is the most important feature (≈52% importance)
- **Mumbai Indians and KKR** are the strongest chasing teams
- Win probability changes significantly in the last 5 overs
- IPL matches remain unpredictable until the final over

---

## 📊 Tableau Dashboard

Interactive Dashboard:

👉 https://public.tableau.com/views/IPLLiveWinProbabilityAnalytics/IPLLiveWinProbabilityAnalyticsDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Dashboard includes:

- Win Probability Curve
- Matches Won by Team
- Pressure Index Analysis
- Match Summary Statistics

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `ipl_win_probability_model.ipynb` | Machine learning notebook |
| `ipl_win_probability.csv` | Ball-by-ball features |
| `ipl_match_summary.csv` | Match-level summary |
| `ipl_feature_importance.csv` | XGBoost feature importance |
| `ipl_win_probability.twbx` | Tableau dashboard |

---

## 🎯 Project Goal

To build a **real-time IPL win probability prediction system** using machine learning and visualize match dynamics through interactive dashboards.

---

## 🚀 Future Improvements

- Real-time API integration
- First innings prediction model
- Player-level analysis
- Deep Learning models
