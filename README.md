# 🏏 IPL Data Visualization using Matplotlib & Seaborn

An exploratory data analysis and visualization project on IPL match data, covering team performances, player awards, batting strategies, and match outcomes using Python.

---

## 📌 Project Overview

This project analyzes IPL match and ball-by-ball delivery data to uncover patterns in team strategies, winning conditions, and player performances. It uses two datasets — `matches.csv` and `deliveries.csv` — to generate insightful charts and statistics.

---

## 📂 Dataset

- **Source:** [Kaggle — IPL Dataset](https://www.kaggle.com/datasets/nowke9/ipldata)
- **Files used:**
  - `matches.csv` — Match-level data (teams, toss, winner, result, city, season)
  - `deliveries.csv` — Ball-by-ball data (runs, dismissals, innings)

---

## 🔍 Analysis Breakdown

### 🏅 Player of the Match
- Count of Man of the Match awards per player
- Top 10 most awarded players
- Bar chart of top 5 players with most awards

### 🎯 Toss Analysis
- Toss winner counts by team
- Correlation between toss win and match win (~52% of the time)

### 🏏 Batting First (Win by Runs)
- Extracted all matches won by the team batting first
- Distribution histogram of winning run margins
- Top 3 teams with most wins batting first
- Pie chart of all teams' win share when batting first

### 🥎 Batting Second (Win by Wickets)
- Extracted all matches won by the team chasing
- Histogram of winning wicket margins
- Top 3 teams with most wins when chasing
- Pie chart of all teams' win share when batting second

### 📅 Season & Venue Analysis
- Number of matches played per season
- Number of matches played in each city

### 📋 Ball-by-Ball Analysis (deliveries.csv)
- Deep dive into a specific match (Match ID: 1 — SRH vs RCB)
- Innings-wise breakdown of batsman runs
- Dismissal types per innings
- Total runs distribution

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| Pandas | Data loading & manipulation |
| NumPy | Numerical calculations |
| Matplotlib | Bar charts, histograms, pie charts |
| Seaborn | Statistical visualizations |
| Google Colab | Development environment |

---

## 🚀 How to Run

### Option 1 — Open in Google Colab
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

*(Replace with your actual Colab notebook link)*

### Option 2 — Run Locally
```bash
git clone https://github.com/anshu1516/IPL-Data-Visualization.git
cd IPL-Data-Visualization

pip install pandas numpy matplotlib seaborn

jupyter notebook Python_project_on_IPL_data.ipynb
```

> **Note:** Download `matches.csv` and `deliveries.csv` from Kaggle and place them in the same directory before running.

---

## 💡 Key Insights

- Toss winners go on to win the match only ~52% of the time — toss advantage is minimal
- Teams generally prefer **chasing** in recent IPL seasons
- A small group of players consistently dominate **Man of the Match** awards

---

## 👤 Author

**Anshu** — [GitHub](https://github.com/anshu1516)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
