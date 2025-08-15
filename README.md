# Player Performance Analytics Using Python & LLMs

This project analyzes lacrosse player performance stats using a CSV dataset of individual game metrics. We apply Python for data exploration and visualize performance trends, then use an LLM (Large Language Model) to answer natural language questions about the dataset — mimicking an interactive, AI-powered sports analyst.

## Dataset Overview

The dataset (Player_Stats.csv) includes individual player statistics such as:

- **Goals (g), Assists (a), Points (pts)**
- **Shooting metrics**: Shots (sh), Accuracy (sh%), Shots on Goal (sog%)
- **Defensive metrics**: Caused Turnovers (ct), Ground Balls (gb), Fouls
- **Game-level stats**: Games Played (gp), Games Started (gs), Cards (rc, yc, gc)

## Key Questions Explored

This project investigates player performance using a structured set of analytical questions:

1. ** How many players are listed in the dataset?**  
2. **What is the average number of goals scored per player?**  
3. **Which player had scored the highest number of goals?**  
4. **Who had the most assists this season?**  
5. **Which player had the highest goals per game ratio?**  
6. **Who had the highest shooting accuracy and shot-on-goal percentage?**  
7. **How many players caused more than 5 turnovers?**  
8. **Which player had the most combined offensive contribution?**  
9. **Who had the highest impact on defense?**  
10. **Was there a correlation between shots taken and goals scored?**  
11. **Who was the most improved player?** *(Based on high efficiency in fewer games played)*

## LLM Integration

A set of player performance questions were posed to an LLM.The goal was to simulate human-like sports reasoning and see how accurately the model could answer data-based questions.

- Prompt responses were crafted based on actual analysis
- Focused on transparency, interpretability, and performance breakdowns
- Files: [LLMResponses] , [playerperformance.ipynb]

---

## Tools Used

-  Python 3.10
-  Pandas, Matplotlib, Seaborn
-  Jupyter Notebook
-  OpenAI ChatGPT
-  Dataset: CSV file (lacrosse player stats)

## Interesting Insights

- **Strong correlation** (r = 0.99) between shots taken and goals scored.
- **Meaghan Tyrrell** had the most goals (54), while **Emma Ward** led in assists (33).
- **Hailey Rhatigan** had the highest shooting accuracy (65%) and SOG% (76%).
- **Emma Ward** had the top offensive contribution (84 total points).
- **Kate Mashewske** made the biggest defensive impact with 123 draw controls.
- **Olivia Adamson** showed remarkable efficiency with 3.33 goals per game in just 3 games.


## How to Run

### Prerequisites

Install Python libraries if not already installed:

```bash
pip install pandas matplotlib seaborn
