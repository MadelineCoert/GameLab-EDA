# 🎮 GameLab EDA – AI vs Traditional Gameplay

This project is an **exploratory data analysis (EDA)** of a simulated experiment run by GameLab, a fictional video game company. The goal of the experiment is to understand whether **AI-driven gameplay features** influence player behavior compared to traditional, non-AI gameplay. The project was completed as part of a university assignment for the course **BSAN7204 – Data Analytics**.

---

## 🧠 Business Problem

GameLab is preparing to launch a new game and is testing whether integrating AI-enhanced features increases player **engagement** and **in-game purchases**, which are key drivers of long-term revenue. Two game versions were tested:

- **Type A**: AI-enhanced gameplay  
- **Type B**: Traditional gameplay (no AI features)

The company wants to know:
- Which version leads to more time spent playing?
- Does one version generate more consistent or higher in-game purchases?
- Should future games focus on immersive AI or consistent playability?

---

## 🔍 Objectives

- Conduct univariate and bivariate analysis to understand user engagement.
- Explore relationships between game type, playtime, experience, and purchases.
- Use statistical testing to determine if differences are significant.
- Provide business recommendations for future game development strategy.

---

## 🛠 Tools and Skills Used

- **Programming**: R  
- **Packages**: `ggplot2`, `dplyr`  
- **Analysis**: Exploratory data analysis, t-tests  
- **Visualization**: Boxplots, histograms, density plots, violin plots  
- **Skills**: Data wrangling, hypothesis testing, storytelling with data  

---

## 📁 Project Structure

game-lab-eda/
├── data/ # Dataset (EDA.csv or simulated version)
├── scripts/ # R code used for data cleaning and analysis
├── visuals/ # Saved graph outputs
├── report/ # Final PDF report (GameLab_EDA_Report.pdf)
└── README.md # Project overview and summary

---

## 📊 Summary of Analysis

### 🔹 Univariate Analysis
- **Hours Played**: Right-skewed distribution. Most users spend moderate time, with a few highly engaged players.
- **Purchases**: Also right-skewed. A small group of players contribute significantly to total in-game spending.
- **Experience Level**: Uneven distribution of player experience could impact comparisons.

### 🔹 Bivariate Analysis
- **Hours by Game Type**: Game A had higher variability and outliers; Game B showed more consistent engagement.
- **Time per Session**: Game B had longer average sessions, suggesting deeper immersion.
- **Purchases by Type**: Game A had higher peaks due to outliers; Game B's purchases were more evenly spread.

### 🔹 Hypothesis Testing (A/B Testing)
- **T-test (Hours)**: Statistically significant difference in mean hours played between game types (p < 0.001)
- **T-test (Purchases)**: Statistically significant difference in mean in-game spending between game types (p < 0.001)

---

## 📌 Key Insights

- **Game A** creates highly engaged users but is more reliant on a small group of power players.
- **Game B** drives more consistent engagement and more predictable spending across the user base.
- From a revenue perspective, Game B may be more scalable and sustainable.
- AI features alone do not guarantee higher performance—it depends on how players interact with the game structure.

---

## 📸 Sample Visual

> Histogram of Hours Played  
> (Saved in `visuals/Hours_Histogram.jpg`)

![Hours Histogram](./visuals/Hours_Histogram.jpg)

---

## 📁 Files Included

| File/Folder | Description |
|-------------|-------------|
| `data/EDA.csv` | Dataset used for analysis (real or simulated) |
| `scripts/eda_script.R` | All R code used for cleaning, EDA, and visualizations |
| `visuals/` | Graphs such as histograms, boxplots, violin plots |
| `report/GameLab_EDA_Report.pdf` | Final report summarizing findings |
| `README.md` | This project overview file |

---

## 📬 Contact

**Madeline Coert**  
📧 madelinecoert@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/madeline-coert-546667309)  
🗂 [Portfolio](https://www.notion.so/Madeline-Coert-Data-Portfolio-230422558f0280ef88b9f306140f1a)
