DAX Measures Documentation for IPL 2025 Power BI Dashboard

This file contains all custom DAX measures used across the 4 pages of the IPL 2025 Power BI Dashboard, categorized by purpose and page.

This document outlines all the key DAX Measures used in the IPL 2025 Power BI Dashboard project. The measures are organized based on the report page in which they are used.

📄 Page 1: Tournament Overview

✅ Core Team Metrics

Total Matches

Total Points

Total Wickets

Total Runs Scored

Total Runs Conceded

Total Wins / Losses

Win %

🥇 Rankings and Performance

Team Rank

Champions

Runner Up

Average Run Rate

Highest Team Score

Lowest Team Score

NRR (Net Run Rate)

📄 Page 2: Team Performance Metrics

📌 Team KPIs

Total Fours

Total Sixes

Top Scorer (Name and Runs)

Top Wicket Taker

Top Fielder (Max Catches)

Total Wickets Taken / Lost

Lowest Score (Conditional by innings and result)

📄 Page 3: Player Performance Metrics

🏏 Batting Metrics

Orange Cap

Total 4s and 6s of the Season

Most Fours (Innings)

Most Sixes (Innings)

Most Fifties / Centuries

Fastest Fifty / Century per Batsman

Highest Scores

Best Batting Averages

Curvv Super Striker of the Season

🎯 Bowling Metrics

Purple Cap

Most Runs Conceded (Innings)

Dot Balls (Tournament and Innings)

Most Maidens

Hat-tricks

Bowling Average

Bowling Strike Rate

Bowling Economy

🧠 Dynamic Metric Selection

Parameter: Batting Metrics, Bowling Metrics

Measure: Selected Measure (for dynamic visuals)

📄 Page 4: Match-Level Insights

⚙️ Worm Chart & Ball-by-Ball KPIs

4s

6s

B (Balls faced excluding wides and no-balls)

Dots

W (Wickets excluding runouts)

O (Overs bowled)

R (Runs excluding legbyes/byes)

RC (Runs conceded including extras)

SR (Strike Rate)

Econ (Economy Rate)

M (Maidens)

This summary ensures all calculated insights are documented clearly, aligning with the modular design of the dashboard.

✅ Notes

Measures are context-sensitive (use of SELECTEDVALUE, slicers)

Visuals include bar charts, card KPIs, line chart, and matrix views

Advanced aggregations use SUMMARIZE, FILTER, TOPN, EARLIER in performance KPIs

For full formulas, explore the Power BI .pbix file.
