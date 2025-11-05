# 🏏 Cricket Analysis – End-to-End Data Analytics Project  

An **end-to-end Cricket Data Analysis** project combining **Web Scraping, Python, Pandas, Power BI, and DAX** to uncover player performance, team trends, and match insights — all displayed through an interactive Power BI dashboard.  

This repository contains a comprehensive Power BI dashboard designed to analyze player performance from the ICC T20 World Cup 2022.

Moving beyond simple scorecards, this project provides a deep, granular analysis of player statistics based on their specific roles (e.g., Opener, Anchor, Finisher). The dashboard is built for interactive exploration, allowing users—such as team analysts, fans, or recruiters—to uncover performance trends, compare players, and understand a player's form against different opponents.

🚀 Key Features & Analytical Insights

This dashboard is designed to uncover deep performance insights into cricket players through powerful analytics and visualization techniques.

1️⃣ Role-Based Player Segmentation

The dashboard is divided into tabs for:
Power Hitters, Anchors, Finishers, All-Rounders, and Specialist Bowlers.

Why: Each role has unique KPIs.

Anchors (like Virat Kohli) → measured by Batting Average

Power Hitters (like Jos Buttler) → measured by Strike Rate & Boundary %

2️⃣ Advanced Player vs Opponent Drill-Through

Select any player from the main dashboard → view detailed stats vs each opponent.

Why: Helps identify a player's strengths and weaknesses.
(Based on visuals like drill pictures section.png)

3️⃣ Interactive Quadrant (Scatter Plot) Analysis

Scatter plots like Batting Avg vs Strike Rate or Economy vs Bowling Strike Rate highlight player archetypes.

Why: Instantly identify consistent high-impact players (top-right quadrant) vs accumulators (bottom-left).

4️⃣ Player Form & Trend Analysis

Dynamic line charts show player form over the tournament.

Why: Understand improvement or decline trends beyond just final averages.

5️⃣ High-Pressure Match Filters

Filter insights by tournament stage — Qualifier vs Super 12.

Why: See which players perform best under pressure.

🧭 Dashboard Structure (Page-by-Page)
Page	Focus	Key Metrics
Power Hitters / Openers	High-impact opening batsmen	Strike Rate, Bat Avg, Boundary %
Anchors / Middle Order	Stability and consistency	Bat Avg, Runs, Balls Faced
Finishers / Lower Order	Impact at innings end	Strike Rate, Avg Balls Faced
All Rounders	Dual contribution (bat + ball)	Bat Avg/SR, Economy, Bowling SR
Drill-Through Page	Player vs Opponent breakdown	Avg, S/R, Economy, Wickets, Runs
🧠 Technical Skills & Tools Demonstrated

Tools & Technologies:

🐍 Python (Web Scraping, Data Cleaning with Pandas)

📊 Power BI (Dashboard, Data Modeling)

🧮 DAX (Custom KPIs and advanced measures)

📈 Excel (Pre-cleaning and data validation)



## 📁 Repository Structure  

| Category | File / Folder | Description |
|-----------|----------------|-------------|
| 🐍 [Analysis.py](analsis_python/Analysis.py) | Python script for data cleaning & processing |
| 📁 [t20_csv_files](t20_csv_files/) | Cleaned CSV datasets |
| 📁 [t20_json_files](t20_json_files/) | Raw JSON files from web scraping |
| 🕸️ [web_scrapping_codes](web_scrapping_codes/) | Scripts for scraping cricket data |
| 📊 [Cricket Analysis Dashboard.pbix](Cricket%20Analysis%20Dashboard.pbix) | Power BI dashboard file |
| 🧮 [measure file helps.xlsx](measure%20file%20helps.xlsx) | DAX measure reference file |
| 📋 [dim_players_no_images.csv](dim_players_no_images.csv) | Final player data CSV |

---

## 🖼️ Dashboard Previews  

| Overview | All-Rounder | Drill Section |
|-----------|-------------|---------------|
| ![Main Dashboard](pictures%20of%20dashboard/Project%20main%20page.png) | ![All Rounder](pictures%20of%20dashboard/all%20rounder.png) | ![Drill Section](pictures%20of%20dashboard/drill%20pictures%20section.png) |

| Finisher Page | Anchor Page |
|----------------|-------------|
| ![Finisher Page](pictures%20of%20dashboard/New%20Finisher%20Page.png) | ![Anchor Page](pictures%20of%20dashboard/New%20Anchors%20page.png) |

Key Technical Highlights:::


DAX Formulas:

Batting Strike Rate = (SUM(Runs) / SUM(Balls Faced)) * 100
Bowling Economy = (SUM(Runs Conceded) / (SUM(Balls Bowled) / 6))
Boundary % = (SUM(Fours)*4 + SUM(Sixes)*6) / SUM(Runs)

Data Modeling: Designed a star schema linking player, match, and opponent data.
Interactive Visuals: Scatter plots, slicers, dynamic line charts, conditional formatting.
UI/UX: Modern dark theme with smooth page navigation.
Drill-Through: Deep player performance insights across dimensions.


📌 How to Use

Clone the repository:

1.git clone https://github.com/your-username/Cricket-Analysis.git
2.Open the Power BI file → cricket_dashboard.pbix
3.Explore different tabs (Power Hitters, Anchors, etc.)
4.Use filters or drill-through to get deeper insights.

💡 Project Learnings

Web Scraping with Python & BeautifulSoup
Data Cleaning and Transformation using Pandas
Power BI Data Modeling and DAX Measures
Analytical storytelling through visual dashboards

🏁 Final Outcome

An end-to-end Data Analytics project showcasing the complete lifecycle — from data extraction → transformation → visualization → insights.
This project highlights technical depth + business understanding, making it an excellent addition to your portfolio or resume.


👨‍💻 Author
Javed Hussain
Email: hussainjaved001100@gmail.com
