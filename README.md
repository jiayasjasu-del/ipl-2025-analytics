# 🏏 IPL 2025 Analytics Dashboard

A hands-on Python data analytics project using **Google Colab** to analyze real IPL 2025 match data with **Pandas**, **Matplotlib**, and **Seaborn** — from raw CSV files to a fully interactive visual dashboard.

---

## 📌 Project Overview

This project walks through loading, cleaning, analyzing, and visualizing IPL 2025 match data across 8 structured tasks, concluding with a bonus Machine Learning challenge to predict match winners.

---

## 🧰 Tools & Libraries

| Tool | Purpose |
|------|---------|
| Google Colab | Cloud-based Python notebook environment |
| Pandas | Data loading, cleaning, and analysis |
| Matplotlib | Chart creation and dashboard layout |
| Seaborn | Styled statistical visualizations |
| Scikit-learn | ML model for match winner prediction (Bonus) |

---

## 📂 Dataset

Download the IPL 2025 dataset from [Kaggle](https://www.kaggle.com/) and place these two files in the same directory:

- `matches.csv` — Match-level data (teams, venue, toss, winner, player of the match)
- `deliveries.csv` — Ball-by-ball data (runs, wickets, batsman, bowler)

---

## 🗂️ Project Structure

```
ipl-2025-analytics/
├── IPL_2025_Analytics_Dashboard.py   # Full source code (all tasks)
├── README.md                         # Project documentation
├── matches.csv                       # (Download from Kaggle)
└── deliveries.csv                    # (Download from Kaggle)
```

---

## 📊 Tasks Covered

| # | Task | Chart Type |
|---|------|-----------|
| 1 | Matches Won per Team | Bar Chart (Pandas) |
| 2 | Most Successful Team | Countplot (Seaborn) |
| 3 | Toss Decision Analysis | Pie Chart |
| 4 | Top 10 Player of the Match | Bar Chart |
| 5 | Venue Analysis | Bar Chart |
| 6 | Team Performance Dashboard | Seaborn Barplot |
| 7 | Winning Percentage | Normalized Bar Chart |
| 8 | Full 2×2 Dashboard | Multi-panel Subplots |
| ⭐ | Bonus: Match Winner Prediction | Random Forest ML |

---

## 🚀 How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Create a new notebook
3. Copy each `# CELL N` block from `IPL_2025_Analytics_Dashboard.py` into separate Colab cells
4. Upload `matches.csv` and `deliveries.csv` when prompted in Cell 2
5. Run cells sequentially from top to bottom

---

## 🤖 Bonus: ML Match Prediction

Uses a **Random Forest Classifier** with:
- Features: `team1`, `team2`, `toss_decision` (label encoded)
- Target: `winner`
- Split: 80% train / 20% test
- Output: Accuracy score + classification report + feature importance chart

---

## 📈 Sample Outputs

Each task saves a chart automatically:

- `task1_wins_bar.png`
- `task2_most_successful.png`
- `task3_toss_pie.png`
- `task4_top_players.png`
- `task5_venues.png`
- `task6_performance_dashboard.png`
- `task7_win_percentage.png`
- `task8_full_dashboard.png`
- `bonus_feature_importance.png`

---

## 📝 Key Learnings

- **Pandas is your foundation** — `read_csv`, `value_counts`, `isnull`, `shape`
- **Clean before you analyze** — always handle nulls before plotting
- **Choose the right chart** — bar for comparisons, pie for proportions, subplots for dashboards
- **ML extends analytics** — predictive modeling builds on the same cleaned data

---

## 👨‍💻 Author

Made as part of a Sports Analytics lab project using real IPL 2025 data.

---

## 📄 License

This project is for educational purposes only. IPL data belongs to its respective owners.

