# 🏏 IPL 2025 Power BI Dashboard

A dynamic and interactive Power BI dashboard to analyze the **Indian Premier League (IPL) 2025** season using ball-by-ball data. This project provides team and player-level insights including batting, bowling, and fielding performances. It also showcases match-wise progression through detailed visuals like the worm chart.

---

## 📊 Project Overview

This Power BI project was built using a **public Kaggle dataset** and includes over 10 interconnected tables modeling ball-by-ball deliveries, player stats, match summaries, and team aggregates. With over 50+ custom DAX measures and calculated tables, the dashboard captures key tournament metrics, helping users visualize:

- Tournament Summary
- Team Performance Metrics
- Player Leaderboards
- Match-Level Insights

---

## 🧰 Tools & Technologies

| Tool           | Description                                     |
|----------------|-------------------------------------------------|
| **Power BI**   | Data modeling, visual design, and DAX measures  |
| **DAX**        | 50+ custom measures across batting, bowling, fielding |

---

## 📂 Folder Structure

IPL-2025-PowerBI-Dashboard/
│
├── assets/ # Screenshots & visual assets
│ ├── dashboard-preview.png
│ ├── data-model.png
│ ├── navigation-bar.png
│ └── page-layouts/
│ ├── page1-overview.png
│ ├── page2-team-performance.png
│ ├── page3-player-performance.png
│ └── page4-match-level-insights.png
│
├── docs/ # Technical documentation
│ ├── DAX_Measures.md
│ ├── Data_Model_Explanation.md
│ └── Project_Features.md
│
├── pbix/
│ └── IPL_2025_Dashboard.pbix # Power BI dashboard file
│
├── README.md

## 📌 Dashboard Pages & Highlights

### 📍 Page 1: Tournament Overview
- **Total Matches, Runs, Sixes, Wickets**
- **Champion & Runner-Up detection**
- **Average Run Rate and NRR**
- **Highest and Lowest Team Scores**

### 📍 Page 2: Team Performance Metrics
- Wins, Losses, Points, and Run Conceded
- Top Scorer, Wicket-Taker, and Fielder (per team)

### 📍 Page 3: Player Performance Leaderboards
- **Batting KPIs**: Orange Cap, Most Sixes, Centuries, Fastest Fifty
- **Bowling KPIs**: Purple Cap, Economy, Maidens, Dot Balls
- Uses **parameterized dynamic charts** with `NAMEOF()` and slicers

### 📍 Page 4: Match-Level Insights
- Over-by-over **Worm Chart**
- Match-wise run progression
- Dot balls, Economy, Overs bowled, Wickets per innings

---

