IPL Analytics - Power BI 

---

1. Project Objective

The objective of this project is to analyze Indian Premier League (IPL) match data using Microsoft Power BI and transform raw match-level data into an interactive analytical dashboard.

The project focuses on identifying patterns in:

Team performance
Match outcomes
Toss impact
Seasonal scoring trends
Venue performance
Match results

The dashboard is designed to provide a clear and interactive overview of IPL match performance and support data-driven interpretation of historical match data.

---

2. Project Overview

This project uses IPL match-level data containing information about teams, toss decisions, match winners, venues, seasons, match results, target runs, target overs, player of the match and other match-related attributes.

Dataset columns

The dataset contains fields including:

- team1
- team2
- match_date
- toss_winner
- toss_decision
- winner
- player_of_match
- venue
- city
- team1_players
- team2_players
- season
- match_number
- match_type
- result
- target_runs
- target_overs
- super_over
- match_year
- toss_impact

---

3. Business Questions

The dashboard was developed to answer the following analytical questions.

3.1 Which are the top 10 venues have the highest scoring pattern across all seasons?
3.2 Does winning the toss have an impact on winning the match?
3.3 Which IPL teams have recorded the highest number of match victories?
3.4 What percentage of matches are won by runs, wickets, do ties, no-results and abandoned matches?
3.5 How does batting intensity(target runs) vary across every season?
3.6 What rate of matches are won by choosing decision as bat versus chase while toss?
3.7 who are the players to take highest number of player of match awards?

---

4. Key Insights

4.1 Venue Analysis
Wankhede stadium records the highest scoring level among the venues analyzed.
The distribution of scoring varies significantly across IPL venues.
A smaller group of venues accounts for a substantial portion of IPL match activity.

4.2 Toss Impact
The toss analysis shows that approximately 50.56% of matches in the current dashboard indicate that the toss winner also won the match.
This suggests that winning the toss alone does not guarantee a match victory.
The relatively balanced distribution between toss impact and no impact indicates that match outcomes depend on factors beyond the toss.

4.3 Team Performance
The analysis identifies Mumbai indians as the team with the highest number of match victories.
Royal challengers bangalore and Rajasthan royals also demonstrate strong historical performance.
Team performance varies considerably across different IPL seasons.

4.4 Seasonal Scoring
The dashboard shows changes in target-run patterns across IPL seasons.
2025/2008 records the highest/lowest value according to the selected scoring metric.
The trend indicates how match scoring patterns have evolved throughout the IPL period.

4.5 Match Results
Matches decided by wickets represent the largest result category.
Matches decided by runs form the second-largest category.
Ties and no-result matches occur considerably less frequently.


---

5. Business Recommendations

Recommendation 1 – Team Strategy
Teams can use historical match-performance data to identify consistently successful opponents, seasons and match conditions and use these patterns when planning future strategies.

Recommendation 2 – Toss Strategy
Since the toss does not guarantee a match victory, teams should avoid treating the toss as the primary determinant of match strategy.

Instead, toss decisions should be evaluated together with:
Venue
Pitch conditions
Team strength
Batting/chasing performance
Historical venue performance

Recommendation 3 – Venue Strategy
Teams can analyze historical venue-level scoring and match outcomes to better understand venue-specific conditions and develop match strategies accordingly.

Recommendation 4 – Performance Benchmarking
Historical team performance can be used to benchmark current team performance and identify areas where teams consistently outperform or underperform.

---

6. Limitations

- The analysis is based on the available historical IPL dataset.
- The dashboard primarily focuses on match-level information.
- Player-level performance analysis is limited by the available fields.
- External factors such as pitch condition, weather, injuries and player fitness are not included.
- Historical trends do not necessarily predict future match outcomes.
- Some derived metrics depend on the definitions and quality of the source dataset.

---

7. Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Visualization
- Data Cleaning
- Data Transformation
- Business Intelligence

--- 

8. Project Structure

IPL-Analytics/
│
├── README.md
│
├── dataset/
│   └── ipl_dataset.csv
│
├── powerbi/
│   └── ipl_analytics.pbix
│
├── dashboard/
│   └── ipl_dashboard.png
│
└── documentation/
    └── ipl_analytics_document.docx

---

9. Documentation

Detailed project documentation is available in:

IPL Analytics Documentation.txt

The documentation includes:
Project Objective
Project Overview
Dataset Information
Business Questions
Key Insights
Business Recommendations
Project Limitations

---

10. Dashboard

The dashboard includes:
- KPI Cards
- Season-wise scoring trend
- Venue analysis
- Team performance
- Toss impact analysis
- Match result distribution
- Interactive filtering

---

Author

Kacharagadla Praveen

Aspiring Data Analyst | Python | SQL | Data Visualization | Data Analytics
