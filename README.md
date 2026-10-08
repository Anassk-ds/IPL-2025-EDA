# 🏏 IPL 2025 Exploratory Data Analysis

**IPL 2025 Exploratory Data Analysis (EDA)** is a data science project by **Shaik Anas**, a B.Tech Data Science student at Chalapathi Institute of Technology.

The project analyzes **IPL 2025 batting and bowling statistics** using Python and data-analysis libraries to explore player performance, team efficiency, all-rounder performance, and relationships between batting and bowling metrics.

> **Project by:** Shaik Anas  
> **Focus:** Data Science • Data Analytics • Exploratory Data Analysis • Sports Analytics

---

## 📌 Project Overview

This project applies an end-to-end **Exploratory Data Analysis (EDA)** workflow to IPL 2025 player statistics.

Rather than relying only on simple averages, the analysis uses **qualification thresholds, weighted metrics, data merging, statistical comparisons, and visualizations** to produce more meaningful comparisons between players and teams.

The project focuses on:

- 🏏 Player batting performance
- 🎯 Player bowling performance
- 🔄 All-rounder performance
- 📊 Team batting efficiency
- 🎳 Team bowling efficiency
- 🔗 Relationship between team runs and wickets
- 📈 Data visualization and correlation analysis

---

## 🎯 Objectives

The main objectives of this IPL 2025 data analysis project are to:

- Analyze individual batting and bowling performances.
- Compare top-performing players with season-wide averages.
- Identify players who contribute in both batting and bowling.
- Evaluate team-level batting and bowling efficiency.
- Compare batting and bowling performance using weighted metrics.
- Study the relationship between total team runs and total team wickets.
- Present analytical findings through clear visualizations.

---

## 🔍 Questions Explored

The analysis answers the following questions:

### 1. 🏏 All-Rounder Performance

For players appearing in both the batting and bowling datasets:

**How does batting strike rate compare with bowling economy rate?**

### 2. 📊 Team Runs

**Which team has the highest combined batting runs?**

### 3. 🎳 Team Wickets

**Which team has the highest combined bowling wickets?**

### 4. ⭐ Top 10 All-Rounders

**What are the strike rate and economy rate of the top 10 all-rounders?**

### 5. 🔗 Team Correlation

**Is there a relationship between total team runs and total team wickets?**

---

## 📂 Dataset

The project uses IPL 2025 player-level batting and bowling statistics.

### Dataset Source

**Kaggle — IPL 2025 Dataset**

The repository does not include the original datasets. They should be downloaded separately and placed in the project directory.

### Required Files

```text
IPL2025Batters.csv
IPL2025Bowlers.csv
```

The datasets contain player-level statistics used for batting, bowling, all-rounder, team, and correlation analysis.

---

## 🧹 Methodology

The project follows a structured data-analysis workflow.

### 1. Data Cleaning

- Checked for missing values.
- Converted data types where required.
- Prepared the batting and bowling datasets for analysis.

### 2. Qualification Filtering

Minimum qualification thresholds were applied to reduce the effect of small sample sizes.

**Batting:**
- Minimum balls faced

**Bowling:**
- Minimum overs bowled

This helps make player comparisons more meaningful.

### 3. All-Rounder Identification

The batting and bowling datasets were merged to identify players who contributed in both disciplines.

This combined dataset was used to compare:

- Batting Strike Rate
- Bowling Economy Rate

### 4. Team-Level Analysis

Team statistics were aggregated to analyze:

- Total runs
- Total wickets
- Batting efficiency
- Bowling efficiency

Weighted metrics were used where appropriate to provide more representative comparisons.

### 5. Visualization

The analysis uses multiple visualization techniques, including:

- 📊 Bar charts
- 📈 Scatter plots
- 🔥 Correlation heatmaps

These visualizations make player and team performance patterns easier to interpret.

---

## 📊 Visualizations

The project generates the following visualizations:

| Visualization | File |
|---|---|
| 🏏 All-Rounder Performance | `all_rounders_plot.png` |
| 📊 Team Runs | `team_runs_plot.png` |
| 🎳 Team Wickets | `team_wickets_plot.png` |
| ⭐ Top 10 All-Rounders | `top10_allrounders_plot.png` |
| 🔗 Team Runs vs Wickets | `team_correlation_plot.png` |
| 🔥 Correlation Heatmap | `team_correlation_heatmap.png` |

### Example

![All-Rounder Performance](all_rounders_plot.png)

![Team Runs](team_runs_plot.png)

![Team Wickets](team_wickets_plot.png)

![Top 10 All-Rounders](top10_allrounders_plot.png)

![Team Runs vs Wickets](team_correlation_plot.png)

![Correlation Heatmap](team_correlation_heatmap.png)

---

## 💡 Key Analytical Observations

The analysis highlights several important patterns:

- Top individual performers can significantly outperform season averages.
- Team batting and bowling efficiencies vary across teams.
- Strong batting efficiency does not necessarily imply equally strong bowling efficiency.
- Team performance can involve a trade-off between batting and bowling strengths.
- Correlation analysis provides a way to examine how effectively teams balance run production and wicket-taking.

> These observations are based on the analysis performed in the project notebook.

---

## 🛠️ Technologies Used

### Programming & Analysis

- 🐍 **Python**
- 🐼 **Pandas**
- 🔢 **NumPy**

### Data Visualization

- 📊 **Matplotlib**
- 🎨 **Seaborn**

### Development Environment

- 📓 **Jupyter Notebook**
- ☁️ **Google Colab**

---

## 📁 Repository Structure

```text
IPL-2025-EDA/
│
├── IPL_2025_EDA.ipynb
├── README.md
│
├── IPL2025Batters.csv          # Download separately
├── IPL2025Bowlers.csv          # Download separately
│
├── all_rounders_plot.png
├── team_runs_plot.png
├── team_wickets_plot.png
├── top10_allrounders_plot.png
├── team_correlation_plot.png
└── team_correlation_heatmap.png
```

> The CSV datasets are not included in the repository and should be obtained separately from the project data source.

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Anassk-ds/IPL-2025-EDA.git
```

### 2. Open the project

```bash
cd IPL-2025-EDA
```

### 3. Open the notebook

Open:

```text
IPL_2025_EDA.ipynb
```

using **Jupyter Notebook** or **Google Colab**.

### 4. Add the datasets

Place these files in the project directory:

```text
IPL2025Batters.csv
IPL2025Bowlers.csv
```

### 5. Run the notebook

Execute the notebook cells sequentially to reproduce the analysis and visualizations.

---

## 📈 What I Learned

This project helped strengthen practical skills in:

- Data cleaning
- Data preprocessing
- Exploratory Data Analysis
- Pandas data manipulation
- Dataset merging
- Statistical comparison
- Weighted metrics
- Data visualization
- Correlation analysis
- Analytical thinking
- Presenting data-driven insights

It also reinforced the importance of **choosing appropriate metrics and avoiding misleading comparisons caused by small sample sizes**.

---

## 🔮 Future Scope

Possible extensions to this project include:

- Match-level IPL 2025 analysis
- Phase-wise batting and bowling analysis
- Powerplay, middle-over, and death-over comparisons
- Comparison of IPL 2025 with previous IPL seasons
- Interactive dashboards
- Additional player performance metrics
- Advanced sports analytics

---

## 👨‍💻 About the Author

### Shaik Anas

**B.Tech Data Science Student | Software Developer | Data Science & ML Enthusiast**

I am interested in **Data Science, Data Analytics, Machine Learning, Python, SQL, and Full-Stack Development**. I enjoy building practical projects and using technology to solve real-world problems.

### 🔗 Connect With Me

- **GitHub:** https://github.com/Anassk-ds
- **LinkedIn:** https://www.linkedin.com/in/shaik-anas-b03a962a8/
- **Portfolio:** https://anassk-ds.github.io/Portfolio-Website/
- **LeetCode:** https://leetcode.com/u/anas_shaik

---

## ⭐ Project

If you find this project useful or interesting, consider giving the repository a ⭐.

**Built with Python, data analysis, and curiosity for cricket analytics. 🏏📊**

---

<div align="center">

### 🚀 Analyze • Learn • Build • Improve

**© Shaik Anas**

</div>
