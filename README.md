# DataVisualization-Project

## Proposal: Analysis of Premier League Match Data (2021-2022)

### Members:
- Thai Ba Hung  
- Tran Le Hai  
- Dang Duc Dat  

## 1. Dataset Description
The data for this project comes from the [Premier League Match Data 2021-2022](https://www.kaggle.com/datasets/evangower/premier-league-match-data) via [Evan Gower](https://github.com/evangower) on Kaggle.

Additionally, we will merge data from the [EPL 21-22 Matches Players dataset](https://www.kaggle.com/datasets/azminetoushikwasi/epl-21-22-matches-players/data?select=all_players_stats.csv) to include player-level performance metrics.

The dataset contains match-level statistics from the 2021-2022 Premier League season, providing insights into team performance, match outcomes, and in-game events. It includes both numerical (e.g., goals, shots, fouls) and categorical (e.g., match outcome, teams) variables.

### Provenance  
- **Data Type:** Structured dataset with match-level and player-level records  
- **Dimensions:** 380 rows x 22 columns (match-level) + player statistics with attributes such as goals, substitutions, and disciplinary records.  

## 2. Reason for Choosing the Dataset  
We are passionate about football, and the Premier League is one of the most exciting and competitive leagues in the world. This dataset allows us to dive deeper into match dynamics, analyze team performances, and explore factors that influence results. By working with real match and player data, we can apply statistical methods to uncover patterns in gameplay, such as team inefficiency or poor player performance. The mix of numerical and categorical variables also provides opportunities for insightful visualizations and comparisons.  

## 3. Research Questions  

### Question 1: Which team performed the worst?  
#### Variables Involved:  
- **FTHG, FTAG:** Full-time goals scored by home and away teams (measuring offensive capability).  
- **FTR:** Full-time result (Win/Loss/Draw) to determine points earned.  
- **HS, AS:** Total shots taken by home and away teams (offensive performance indicator).  
- **HST, AST:** Shots on target by home and away teams (measuring efficiency).  
- **HF, AF:** Fouls committed by home and away teams (indicating recklessness or undisciplined play).  
- **HY, AY:** Yellow cards received by home and away teams.  
- **HR, AR:** Red cards received by home and away teams.  
- **HC, AC:** Corners won by home and away teams (showing attacking intent).  
- **Date:** Timeframe of poor performances, to track consistency.  

#### Analysis Approach:
- **Goal efficiency:** Teams with the lowest goals per match will be identified.  
- **Shot conversion:** Compare shots taken vs. goals scored to determine attacking inefficiency.  
- **Discipline:** Teams with the highest fouls, yellow, and red cards will be analyzed for reckless play.  
- **Consistency over time:** Identify whether poor performances are consistent throughout the season or if they improved/worsened over time.  

We will analyze teams that consistently score the fewest goals, take inefficient shots, earn the fewest points, and have high foul/card counts to determine the worst-performing team.  

### Question 2: Which players should be sold?  
To evaluate players who should be sold, we will merge the match dataset with player statistics to analyze individual performance.

#### Variables Involved:
- **Team:** The team the player belongs to.  
- **JerseyNo:** Jersey number of the player.  
- **Player:** Name of the player.  
- **Position:** Playing position (e.g., forward, midfielder, defender).  
- **Appearances:** Total appearances in the season.  
- **Substitutions:** Number of times substituted.  
- **Goals:** Total goals scored.  
- **Penalties:** Total penalties scored.  
- **YellowCards:** Number of yellow cards received.  
- **RedCards:** Number of red cards received.  

#### Analysis Approach:
- **Underperforming strikers:** Compare goals scored vs. expected goals (xG) to identify inefficient forwards.  
- **Defensive errors:** Look at fouls, yellow/red cards, and conceded goals to identify weak defenders.  
- **Midfield contributions:** Assess assists, key passes, and possession stats to evaluate midfielders.  
- **Frequent substitutions:** Players with high substitution rates but low performance metrics may indicate a lack of consistency.  

By combining player performance data with match results, we can rank underperforming players and suggest which ones should be sold.  

## 4. Plan for Analysis  
For identifying the worst team, we will analyze goal-scoring performance, disciplinary records, shot conversion rates, and overall match outcomes over time. We will use bar charts, scatter plots, and heatmaps to highlight patterns in poor performance.  

For player sales, we will evaluate player performance across multiple attributes, including goal contributions, disciplinary records, and substitution frequency. Visualization techniques such as histograms, scatter plots, and ranking tables will be used to highlight underperforming players.  

## 5. Conclusion  
This analysis will help identify the weakest team in the 2021-2022 Premier League season and suggest which players should be sold based on their performance. The findings will be supported by data visualizations such as heatmaps, scatter plots, and trend lines. By integrating match and player statistics, we aim to develop actionable insights for improving team performance and squad management.
