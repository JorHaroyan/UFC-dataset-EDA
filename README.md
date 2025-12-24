# UFC Dataset Exploratory Data Analysis (EDA)

## Overview
This project performs an **exploratory data analysis (EDA)** on UFC fight data. The goal is to analyze fighters’ demographics, physical attributes, career statistics, and fight outcomes to uncover trends, patterns, and insights.  

As a UFC fan, I combined my passion for the sport with data analysis to better understand factors influencing fight results and trends over time. This project is also useful for exam preparation in data analysis courses.

## Dataset
The dataset is available on Kaggle:  
[Ultimate UFC Dataset](https://www.kaggle.com/datasets/mdabbert/ultimate-ufc-dataset)  

It contains **6528 fights** with **120 columns**, including:  
- Fighter information: Name, age, country, gender  
- Physical attributes: Height, reach, weight class  
- Fight stats: Wins, losses, draws, win streaks  
- Betting odds: RedOdds, BlueOdds, expected values  
- Fight details: Finish method, rounds, time  
- Rankings and performance metrics

## Objectives
1. **Understand the dataset structure:** Check column types, missing values, and summary statistics.  
2. **Analyze fighter characteristics:** Compare Red vs Blue corner fighters on age, height, reach, and win streak differences.  
3. **Examine fight outcomes:** Look at winners, finish types, weight class distributions, and trends over time.  
4. **Explore betting odds:** Calculate favorite win percentage to see if odds predict outcomes.  
5. **Visualize key metrics:** Use plots to detect patterns and relationships.  
6. **Prepare for further modeling:** Clean and feature-engineer data for potential predictive models.

## Key Analyses
1. **Data overview:** Displayed shape, columns, data types, first rows, and summary statistics.  
2. **Missing values:** Identified columns with missing values (e.g., odds, rankings, fight finishes).  
3. **Target variable:** Examined `Winner` distribution (Red wins: 3787, Blue wins: 2741).  
4. **Weight class analysis:** Number of fights per weight class.  
5. **Fight outcomes:** Count of different finishes (KO, submission, decision) by weight class.  
6. **Trends over time:** Number of fights per year.  
7. **Correlation analysis:** Between `HeightDif`, `ReachDif`, `AgeDif`, `WinStreakDif`, and fight outcome.  
8. **Favorite win analysis:** Calculated that favorites win **62.67% of fights**.

## Libraries Used
- `pandas` – Data manipulation and cleaning  
- `numpy` – Numerical calculations  
- `matplotlib` & `seaborn` – Data visualization  

## How to Use
1. Clone the repository:  
```bash
git clone https://github.com/YOUR_USERNAME/UFC-dataset-EDA.git

