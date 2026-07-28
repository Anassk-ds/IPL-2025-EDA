# IPL 2025 Exploratory Data Analysis (EDA)

**Author:** Shaik Anas  

This project performs an **exploratory data analysis** (EDA) on the IPL 2025 season, focusing on both **individual and team-level performance** using batting and bowling statistics. The analysis was done to regain hands-on coding practice and to apply structured analytical thinking to a real-world sports dataset.

---

## Overview

Instead of relying on raw aggregates, this project emphasizes **fair comparisons**, **weighted metrics**, and **visualizations** to extract meaningful insights from the data.

The project explores **all-rounder performance**, **team efficiency**, and correlations between batting and bowling across teams.

---

## Objectives

- Analyze individual batting and bowling performances in IPL 2025  
- Compare top performers against season-wide averages  
- Evaluate team-level batting and bowling efficiency using weighted metrics  
- Study the balance between batting and bowling efficiency across teams  

---

## Questions Explored

1. **All-Rounders:** For players who appear in both batting and bowling datasets, compare their **batting strike rate** with their **bowling economy rate**.  
2. **Team Runs:** Which team has the **highest combined runs** (sum of runs of all its batters)?  
3. **Team Wickets:** Which team has the **highest combined wickets** (sum of wickets of all its bowlers)?  
4. **Top 10 All-Rounders:** What is the **economy rate** and **strike rate** of the top 10 all-rounders?  
5. **Team Correlation:** Is there a correlation between **total team runs** and **total team wickets**?

---

## Dataset

- Source: Kaggle (IPL 2025 dataset)  
- Includes **player-level batting and bowling statistics**  
- Not uploaded to this repo due to licensing — please download from Kaggle  

--

## Methodology

1. **Data Cleaning**  
   - Checked for missing values  
   - Converted data types where necessary  

2. **Filtering**  
   - Applied minimum qualification thresholds to avoid small-sample bias  
     - Batting: minimum balls faced  
     - Bowling: minimum overs bowled  

3. **Analysis**  
   - Merged datasets to identify all-rounders  
   - Calculated weighted metrics for team efficiency  
     - **Weighted Strike Rate** for batting  
     - **Weighted Economy Rate** for bowling  

4. **Visualization**  
   - Scatter plots, bar charts, and heatmaps to summarize findings  

---

## Key Insights

- Top individual performers significantly outperformed season averages  
- Team batting and bowling efficiencies show clear variation  
- No team dominated both batting and bowling efficiency, showing a **trade-off**  
- Correlation analysis highlights which teams balance runs and wickets effectively  

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Usage

1. Open the `IPL_2025_EDA.ipynb` notebook in Jupyter Notebook or Google Colab  
2. Upload the datasets:  
   - `IPL2025Batters.csv`  
   - `IPL2025Bowlers.csv`  
3. Run all cells  
4. All plots will be saved automatically as PNG files in the notebook folder  

---

## Visualizations

- **All-Rounders Plot:** `all_rounders_plot.png`  
- **Team Runs:** `team_runs_plot.png`  
- **Team Wickets:** `team_wickets_plot.png`  
- **Top 10 All-Rounders:** `top10_allrounders_plot.png`  
- **Team Runs vs Wickets Scatter Plot:** `team_correlation_plot.png`  
- **Correlation Heatmap:** `team_correlation_heatmap.png`  

> You can embed these images in your GitHub README using Markdown:
>
> ```markdown
> ![All-Rounders](all_rounders_plot.png)
> ```

---

## Conclusion

This project reinforced the importance of:

- Thinking before coding  
- Defining **fair metrics**  
- Avoiding misleading averages  

It also served as a **practical exercise** to regain analytical momentum while building an **end-to-end EDA workflow** on a real-world dataset.

---

## Future Scope

- Extend analysis to **match-level or phase-wise performance**  
- Compare IPL 2025 trends with **previous seasons**  
- Incorporate **interactive visualizations** or dashboards
