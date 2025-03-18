# DataVisualization-Project
# **Proposal: Analysis of Premier League Match Data (2021-2022)**

## **1. Dataset Description**
The dataset contains match-level statistics from the **2021-2022 Premier League season**, including details on team performance, match outcomes, and various in-game events. It includes both **numerical** (e.g., goals, shots, fouls) and **categorical** (e.g., match outcome, referee, teams) variables.

### **Provenance**
- **Data Type:** Structured dataset with match-level records
- **Dimensions:** Match data, teams, scores, results, referee, statistics on shots, cards

## **2. Reason for Choosing the Dataset**
The **Premier League is one of the most competitive football leagues in the world**, making it a compelling dataset for **performance analysis and storytelling**. This dataset allows for an exploration of key **game dynamics, team strategies, and correlations between playing styles and success rates**. The variety of numerical and categorical variables makes it ideal for visualization and statistical modeling.

## **3. Research Questions**

### **Question 1: How does shot accuracy impact match results?**
#### **Involved Variables:**
- **Shots on Target by Home Team (HST) (Numerical)**
- **Shots on Target by Away Team (AST) (Numerical)**
- **Full-time Result (FTR) (Categorical)**

#### **Plan for Analysis:**
- Compare shot accuracy between winning and losing teams.
- Use **scatter plots** and **correlation matrices** to explore trends.
- Consider external data such as **player shooting efficiency** to enhance insights.

### **Question 2: How does disciplinary record (fouls and cards) correlate with match outcomes?**
#### **Involved Variables:**
- **Fouls by Home Team (HF) (Numerical)**
- **Fouls by Away Team (AF) (Numerical)**
- **Yellow Cards (HY, AY) (Numerical)**
- **Red Cards (HR, AR) (Numerical)**
- **Full-time Result (FTR) (Categorical)**

#### **Plan for Analysis:**
- Compare **win rates** of teams with different levels of fouls and cards.
- Use **bar charts** to examine trends in fouls vs. success rate.
- Explore external data such as **referee tendencies** (some referees may issue more cards) to adjust for bias.

## **4. Conclusion**
This analysis will provide insights into whether teams should prioritize **shot efficiency** or focus on **aggressive vs. disciplined playstyles**. The findings will be supported by visualizations such as heatmaps, scatter plots, and trend lines. By combining match statistics with potential external datasets, we aim to develop actionable insights for understanding **what contributes to success in the Premier League**.
