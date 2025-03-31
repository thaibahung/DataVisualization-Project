# DataVisualization-Project

## Proposal: Analysis of Premier League Match Data (2021-2022)

### Members:
- Thai Ba Hung  
- Tran Le Hai  
- Dang Duc Dat  

## 1. Dataset Description
The data for this project comes from the [Premier League Match Data 2021-2022](https://www.kaggle.com/datasets/evangower/premier-league-match-data) via [Evan Gower](https://github.com/evangower) on Kaggle.

The dataset contains match-level statistics from the 2021-2022 Premier League season, providing insights into team performance, match outcomes, and in-game events. It includes both numerical (e.g., goals, shots, fouls) and categorical (e.g., match outcome, teams) variables.

### Provenance  
- **Data Type:** Structured dataset with match-level records  
- **Dimensions:** 380 rows x 22 columns with various types like match data, teams, scores, results, offensive and defensive stats.  

## 2. Reason for Choosing the Dataset  
We are passionate about football, and the Premier League is one of the most exciting and competitive leagues in the world. This dataset allows us to dive deeper into match dynamics, analyze team performances, and explore factors that influence results. By working with real match data, we can apply statistical methods to uncover patterns in gameplay, such as team inefficiency or poor player performance. The mix of numerical and categorical variables also provides opportunities for insightful visualizations and comparisons.  

## 3. Research Questions  

### Question 1: Which team performed the worst?  
#### Variables Involved:  
- **FTHG, FTAG:** Full-time goals scored by home and away teams (measuring offensive capability).  
- **FTR:** Full-time result (Win/Loss/Draw) to determine points earned.  
- **HF, AF:** Fouls committed by home and away teams (indicating recklessness or undisciplined play).  
- **HY, AY:** Yellow cards received by home and away teams.  
- **HR, AR:** Red cards received by home and away teams.  

We will analyze teams that consistently score the fewest goals, earn the fewest points, and have high foul/card counts to determine the worst-performing team.  

### Question 2: Which players should be sold?  
#### Potential Approach (if player-level data is available):  
- **Underperforming strikers:** Compare goals scored vs. expected goals (xG) to identify inefficient forwards.  
- **Defensive errors:** Look at fouls, yellow/red cards, and conceded goals to identify weak defenders.  
- **Midfield contributions:** Assess assists, key passes, and possession stats to evaluate midfielders.  

Since the dataset does not include player-level statistics, we may need to incorporate external data to rank underperforming players and suggest potential sales.  

## 4. Plan for Analysis  
For identifying the worst team, we will analyze goal-scoring performance, disciplinary records, and overall match outcomes. We will use bar charts, scatter plots, and heatmaps to highlight patterns in poor performance.  

For player sales, if additional data is available, we will rank underperforming players based on efficiency metrics such as expected goals, defensive contributions, and playmaking ability.  

## 5. Conclusion  
This analysis will help identify the weakest team in the 2021-2022 Premier League season and suggest which players should be sold based on their performance. The findings will be supported by data visualizations such as heatmaps, scatter plots, and trend lines. By integrating match statistics with potential external datasets, we aim to develop actionable insights for improving team performance and squad management.
