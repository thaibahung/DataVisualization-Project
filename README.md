# DataVisualization-Project
# Proposal: Analysis of Premier League Match Data (2021-2022)

## 1. Dataset Description
The dataset contains match-level statistics from the 2021-2022 Premier League season, providing insights into team performance, match outcomes, and in-game events. It includes both numerical (e.g., goals, shots, fouls) and categorical (e.g., match outcome, teams).  

### Provenance  
- **Source:** [Premier League Official Data / Public Repository]  
- **Data Type:** Structured dataset with match-level records  
- **Dimensions:** Match data, teams, scores, results, offensive and defensive stats.  

## 2. Reason for Choosing the Dataset  
This dataset was chosen because the Premier League is one of the most competitive football leagues globally, making it ideal for performance analysis and storytelling. The dataset allows us to explore key game dynamics, team strategies, and factors influencing match outcomes. The combination of numerical and categorical variables makes it well-suited for visualization and statistical modeling.  

## 3. Research Questions  

### Question 1: How does shot accuracy impact match results?  
#### Variables Involved:  
- Shots on Target by Home Team (HST) (Numerical)  
- Shots on Target by Away Team (AST) (Numerical)  
- Full-time Result (FTR) (Categorical)  


### Question 2: How does disciplinary record (fouls and cards) correlate with match outcomes?  
#### Variables Involved:  
- Fouls by Home Team (HF) (Numerical)  
- Fouls by Away Team (AF) (Numerical)  
- Yellow Cards (HY, AY) (Numerical)  
- Red Cards (HR, AR) (Numerical)  
- Full-time Result (FTR) (Categorical)  

## 4. Plan for Analysis  

For shot accuracy, we will calculate the ratio of shots on target to total shots and analyze whether teams with higher accuracy have better results. Scatter plots and comparisons across match outcomes will help visualize trends.  

For disciplinary records, we will examine how fouls and cards influence a team's chances of winning. Bar charts and heatmaps will highlight differences between aggressive and disciplined teams.  

To provide deeper insights, external data such as league standings can be merged to compare stats with final rankings, or possession statistics can be used to see if aggressive teams have lower ball control.  
## 5. Conclusion  
This analysis will provide insights into whether teams should prioritize shot efficiency or focus on aggressive vs. disciplined playstyles. The findings will be supported by visualizations such as heatmaps, scatter plots, and trend lines. By combining match statistics with potential external datasets, we aim to develop actionable insights for understanding what contributes to success in the Premier League.  
