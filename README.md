## 📊 IPL Team Performance Analysis

## 🔹 Project Overview

This project is an interactive **Microsoft Excel dashboard** built using IPL 2025 match and player performance data.

The dashboard analyzes **team performance, match results, batting, bowling, player contributions, and venue performance** during the 2025 IPL season.

---

## 🔹 Business Objectives

The main objective of this project is to understand **how IPL teams performed and what factors contributed to their results**.

The dashboard aims to answer questions such as:

* Which teams performed the best during IPL 2025?
* Which teams were the most consistent in winning matches?
* How did teams perform in terms of runs and wickets?
* Which players made the biggest contributions to their teams?
* Which teams had stronger batting or bowling performances?
* Does winning the toss appear to influence match results?
* Which venues produced the most wins or highest-scoring matches?
* Which players had the strongest batting and bowling performances?
* Which teams performed better against specific opponents?

*These objectives can be expanded or refined as the analysis progresses.*

---

## 🔹 Tools & Technologies

* Microsoft Excel
* Power Query Editor
* Power Pivot
* Excel Data Model
* Pivot Tables
* Pivot Charts
* Excel Formulas
* Slicers / Filters
* Dashboard Design

---

## 🔹 Dataset Overview

The project uses structured IPL 2025 data divided into **dimension and fact tables**.

### Dimension Tables

* `dim_team` — Contains team information such as team name, captain, coach, home ground, city, and owner.
* `dim_player` — Contains player information such as role, nationality, batting style, and bowling style.
* `dim_venue` — Contains venue information such as venue name, city, and capacity.

### Fact Tables

* `fact_match` — Contains match-level information such as date, teams, toss winner, match winner, scores, wickets, and overs.
* `fact_player` — Contains player-level performance such as runs, balls faced, fours, sixes, strike rate, overs bowled, runs conceded, wickets, and economy.

### Dataset Link

[IPL 2025 Team Performance Dataset](https://github.com/Chauhanekta21/IPL_Team_Performance_Analysis/blob/main/Dataset/ipl_raw_data.xlsx)

---

## 🔹 Analytics Workflow

```text
Raw Dataset
    ↓
Data Import
    ↓
Data Cleaning
    ↓
Data Transformation
    ↓
Data Load
    ↓
Data Modeling
    ↓
Calculated Columns & Metrics
    ↓
Pivot Tables
    ↓
Charts & Visualizations
    ↓
Slicers / Filters
    ↓
Interactive Excel Dashboard
```
