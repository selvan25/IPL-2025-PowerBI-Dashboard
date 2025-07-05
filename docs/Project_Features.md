This document outlines the main features and highlights of the IPL 2025 Power BI Dashboard project.

**🌐 Project Overview**

 The dashboard analyzes the complete IPL 2025 season using publicly available ball-by-ball and match-level datasets. It provides deep insights into teams, players, and matches using advanced DAX, Power BI visuals, and dynamic slicers.

**📋 Key Features by Page**

  📄 Page 1: Tournament Overview

      Average Run Rate, Total Points, Wins/Losses, and NRR

      Champion and Runner-Up detection using DAX logic

      Rank calculation using RANKX

      KPIs for total 4s, 6s, wickets, and matches

  📄 Page 2: Team Performance Metrics

      Team-wise drilldown using Teams slicer

      Top run scorer and wicket taker per team

      Fielding impact: most catches

      Total runs scored, runs conceded, wins, losses, and wickets

      Dynamic lowest score logic based on innings and match result

  📄 Page 3: Player Performance Metrics

      Dynamic metric selection using Batting Metrics and Bowling Metrics parameters

      Leaderboards for:

        Orange Cap / Purple Cap

        Most 4s, 6s, fifties, centuries

        Fastest 50s / 100s

        Best averages, strike rates, economy rates

        Most maidens, dot balls, hat-tricks

  📄 Page 4: Match-Level Insights

        Worm chart using calculated table WormChartData

        Scorecard stats: dots, 4s, 6s, W (Wickets excluding runouts), O (Overs bowled), R (Runs excluding legbyes/byes), 
                         RC (Runs conceded including extras), SR (Strike Rate), Econ (Economy Rate), M (Maidens)


  🧠 Technical Highlights

      Over 50 DAX measures with dynamic logic

      Use of calculated columns like Over_Number, BallNumber_Faced_By_Striker

      Dynamic parameter-based metric switching using NAMEOF and SELECTEDVALUE

      Custom visuals like worm chart, leaderboards, and performance cards

      Clean data model with Fact-Dimension relationships

  🎯 Target Use Cases

    Showcasing end-to-end Power BI project skills

    Resume/portfolio presentation for Data Analyst roles

    Demonstrating DAX proficiency

This project combines data modeling, visualization, and performance storytelling into one cohesive and impactful dashboard.
