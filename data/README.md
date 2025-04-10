# ⚽ Soccer Dataset (2021–2022 Season)

This repository contains two datasets providing detailed statistics and metadata from professional soccer matches during the 2021–2022 season. The data can be used for sports analytics, performance analysis, and machine learning applications.

---

## 📂 Dataset Files

- `all_players_stat.csv`: Contains individual player statistics across the season.
- `soccer21_22.csv`: Contains match-level data from the 2021–2022 season.

---

## 🧾 Metadata and Provenance

**Source**:  
The datasets are compiled from publicly available match data and player performance statistics during the 2021–2022 soccer season. If you're using this dataset for academic or commercial purposes, ensure to cite or acknowledge the original data source if applicable.

**License**:  
MIT License or Data Use agreement based on original source provider.

**Last Updated**:  
April 2025

---

## 🧰 Codebook

### 1. `all_players_stat.csv`

| Column Name   | Description                                                   |
|---------------|---------------------------------------------------------------|
| Team          | The name of the team the player represents                    |
| JerseyNo      | Player’s jersey number                                        |
| Player        | Full name of the player                                       |
| Position      | Player’s position (e.g., Goalkeeper, Defender, Midfielder)    |
| Apearances    | Total number of matches the player appeared in                |
| Substitutions | Number of times the player was substituted in/out             |
| Goals         | Number of goals scored by the player                          |
| Penalties     | Number of penalties scored                                    |
| YellowCards   | Number of yellow cards received                               |
| RedCards      | Number of red cards received                                  |

> ⚠️ Note: The column name "Apearances" is kept as in the original dataset, though the correct spelling is "Appearances".

---

### 2. `soccer21_22.csv`

| Column Name | Description                                                   |
|-------------|---------------------------------------------------------------|
| Date        | Match date (YYYY-MM-DD)                                       |
| HomeTeam    | Name of the home team                                         |
| AwayTeam    | Name of the away team                                         |
| FTHG        | Full-time home team goals                                     |
| FTAG        | Full-time away team goals                                     |
| FTR         | Full-time result (H = Home win, D = Draw, A = Away win)       |
| HTHG        | Half-time home team goals                                     |
| HTAG        | Half-time away team goals                                     |
| HTR         | Half-time result (H = Home win, D = Draw, A = Away win)       |
| Referee     | Name of the match referee                                     |
| HS          | Home team total shots                                         |
| AS          | Away team total shots                                         |
| HST         | Home team shots on target                                     |
| AST         | Away team shots on target                                     |
| HF          | Home team fouls committed                                     |
| AF          | Away team fouls committed                                     |
| HC          | Home team corners                                             |
| AC          | Away team corners                                             |
| HY          | Home team yellow cards                                        |
| AY          | Away team yellow cards                                        |
| HR          | Home team red cards                                           |
| AR          | Away team red cards                                           |

---

## 🔍 Use Cases

- Player performance modeling
- Match outcome prediction
- Referee bias analysis
- Visualization of team stats over time

---

## 📌 Notes

- Missing values should be handled appropriately during preprocessing.
- Ensure data normalization if combining both datasets for analysis.

---
