# 🏏 IPL 2022 Data Analysis

This project provides a comprehensive data analysis of the 2022 Indian Premier League (IPL) season using Python and Pandas. It explores match outcomes, team performance trends, toss decisions, venue impacts, and other key insights.

---

## 📊 Dataset

- **Source**: Custom CSV file containing IPL 2022 match-level data.
- **Columns Include**:
  - `match_id`, `date`, `venue`, `team1`, `team2`
  - `toss_winner`, `toss_decision`, `match_winner`
  - `first_ings_score`, `second_ings_score`, `won_by`, `margin`
  - `player_of_the_match`, `top_scorer`, `best_bowling`, etc.

---

## 🔍 Key Questions Solved

### 🔹 Intermediate Analysis
- ✅ Which team has the highest win percentage?
- ✅ What are the toss decision trends?
- ✅ Which venues are most successful for home teams?

### 🔹 Advanced Analysis
- ✅ Is there a correlation between toss winners and match winners?
- ✅ What is the win rate for teams batting first vs fielding first?
- ✅ How have Mumbai Indians performed over time (based on available data)?

---

## 🛠️ Tools & Libraries Used

- Python 3.x  
- Pandas  
- NumPy  
- Jupyter Notebook  
- Matplotlib / Seaborn *(optional for visualization)*

---

## 📁 Files

- `IPL.csv` – Raw dataset
- `Ipl2022_analysis.ipynb` – Jupyter notebook with full analysis and code
- `README.md` – Project overview

---

## 📌 Insights Summary

- **Gujarat** had the highest win percentage (75%) in IPL 2022.
- Most captains preferred to **field first** after winning the toss.
- **Wankhede** and **DY Patil Stadiums** had the highest home team wins.
- Batting first led to **59% win rate**, despite the popular trend of chasing.
- **Mumbai Indians** had just **1 win** in the 2022 data provided.

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/khankaif17/ipl-2022-analysis.git
   cd ipl-2022-analysis
2. pip install pandas numpy
3. jupyter notebook Ipl2022_analysis.ipynb

📌 License
This project is licensed under the MIT License - feel free to use and modify.
