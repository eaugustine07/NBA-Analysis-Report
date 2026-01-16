# 🏀 NBA Player Data Analysis (2021–2022 Season)

**Course:** CSCI2000U – Scientific Data Analysis  
**Assignment:** Assignment 1 – NBA Data Analysis  
**Author:** Einsten Augustine  
**Dataset Source:** Kaggle  

---

## 📌 Project Overview

This project explores **NBA player statistics from the 2021–2022 season** using Python-based data analysis and visualization techniques. The dataset contains information on **558 active NBA players**, including age, height, weight, salary, team, and position.

The goal of this analysis is to uncover trends and relationships between **player demographics, physical attributes, positions, and salaries**, using exploratory data analysis (EDA) and visualizations.

---

## 🎯 Research Questions & Hypotheses

The analysis focuses on the following key questions:

1. **Does player salary increase with age?**  
   - Hypothesis: Salaries generally increase as players enter their prime years.

2. **Which NBA position earns the highest salary on average?**  
   - Hypothesis: Guards tend to earn more due to scoring and playmaking roles.

3. **How do physical attributes (height and weight) vary by position?**  
   - Hypothesis: Centers are taller and heavier, while guards are shorter and lighter.

---

## 📊 Dataset Description

- **Total Players:** 558  
- **Columns:** 9  

### Key Features:
| Column | Description |
|------|-------------|
| Name | Player name |
| Team | NBA team |
| Position | Player position |
| Age | Player age |
| Height | Height (string format) |
| Height_i | Height (numeric, feet) |
| Weight | Weight (lbs) |
| College | College attended |
| Salary | Annual salary (USD) |

Missing values are present mainly in:
- **Salary (~20%)**
- **College (~13%)**

---

## 🧹 Data Cleaning & Preparation

The following steps were performed:

- Converted string `"nan"` values to actual `NaN`
- Converted numerical columns to proper data types
- Handled missing salary and college values
- Verified no duplicate player entries
- Categorized player positions into:
  - Guard
  - Forward
  - Center

---

## 📈 Exploratory Data Analysis (EDA)

### Descriptive Statistics
Basic statistics (mean, median, quartiles, min/max) were computed for:
- Age
- Height
- Weight
- Salary

### Visualizations Include:
- **Salary distribution histogram**
- **Age group salary analysis**
- **Average height and weight by position**
- **Salary comparison across positions**
- **Age vs salary trend**
- **Top 15 highest-paid NBA players**

---

## 🔍 Key Findings

- **Physical Attributes by Position**
  - Centers are the tallest and heaviest players
  - Guards are shorter and lighter
  - Forwards fall in between

- **Salary Distribution**
  - Most players earn under $5 million annually
  - A small group of elite players earns significantly higher salaries
  - High salaries skew the mean, making the median more representative

- **Age vs Salary Trend**
  - Salaries rise as players enter their prime years
  - Peak earnings occur during veteran years
  - Salaries decline as players approach retirement

- **Position vs Salary**
  - Guards earn slightly more on average
  - Overall salary differences by position are relatively balanced

---

## ⚠️ Limitations

- No in-game performance statistics (e.g., points, rebounds, assists)
- Salary missing for ~20% of players
- Does not account for contract length, bonuses, or injuries

A more comprehensive dataset could improve predictive insights.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab / Jupyter Notebook**

---

## 📂 Project Structure
