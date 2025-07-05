This document describes the data model design and relationships used in the IPL 2025 Power BI Dashboard.


**🧩 Data Tables Used**

  **🎯 Fact Table**

      ipl_2025_deliveries: Ball-by-ball data including runs, wickets, extras, and over details.

      Matches: Match metadata including match_id, venue, date, and phase.

 ** 📊 Dimension & Calculated Tables**

      TeamTotalsTable: Aggregated metrics like team totals, overs, points, wickets, etc.

      Striker_Stats: Player-wise batting aggregates.

      Bowler_Stats: Player-wise bowling aggregates.

      Fielding_Stats: Player-wise fielding aggregates.

      Teams: Lookup table for all team names.

      PointsTable : Calculated table to summarize points and assign position. 

      WormChartData: Created using SUMMARIZE for building over-wise run progression (worm chart).


 ** 🔗 Relationships**

    ✅ Primary Key Relationships

          ipl_2025_deliveries[match_id] → Matches[match_id]

          ipl_2025_deliveries[batting_team] → Teams[Team]

          ipl_2025_deliveries[striker] → Players[player]

          ipl_2025_deliveries[bowler] → Players[player]

          TeamTotalsTable[batting_team] → Teams[Team]

    🔄 Supporting Relationships

          Striker_Stats[Team] → Teams[Team]

          Bowler_Stats[Team] → Teams[Team]

          Fielding_Stats[Team] → Teams[Team]

          Striker_Stats[striker] → Players[player]

          Bowler_Stats[bowler] → Players[player]

          Fielding_Stats[fielder] → Players[player]


**  ⚙️ Parameter Tables**

      Batting Metrics and Bowling Metrics parameters used to dynamically switch between KPIs on Page 3.

**🗂️ Key Notes**

Star schema is followed where possible.

Calculated columns like Over_Number, BallNumber_Faced_By_Striker are used for advanced visuals and performance KPIs.

This structure ensures a clean, scalable, and responsive Power BI model that supports detailed cricket analytics.

