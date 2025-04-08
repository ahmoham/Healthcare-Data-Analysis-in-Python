# 🏥 Healthcare Data Analysis in Python

**Author:** Abdullahi Mohamed  
**Date:** April 4, 2025  

## 📋 Overview

In this project, I explored a sample healthcare dataset using **Python**, focusing on **data cleaning**, **manipulation**, and **exploratory data analysis (EDA)**. The goal was to improve data quality and uncover insights about hospital admissions, billing amounts, and patient conditions.

📂 [Click here to view the dataset](https://www.kaggle.com/datasets/prasad22/healthcare-dataset/data).

## 🔧 Process

### 1. Prepare
- 📚 Imported essential libraries: **Pandas**, **NumPy**, **Seaborn**, **Matplotlib**.
- 🧹 Cleaned the dataset by:
  - Standardizing column names for easy querying.
  - Handling missing values and removing duplicates.
  - Correcting date formats for admission and discharge dates.
  - Creating a new feature: `length_of_stay`.
  - Formatting patient names and rounding billing amounts.

### 2. Analyze
- 💵 Explored billing amounts by **medical condition**, **gender**, and **insurance provider**.
- 🏥 Analyzed **length of hospital stay** by hospital and by medical condition.
- 📊 Visualized relationships using **crosstabs** and a **heatmap**.

## ✨ Key Findings

- The dataset had **very little variability** — many features contained identical or nearly identical values.
- Because of this, it was difficult to uncover meaningful patterns or trends.
- This reinforced the importance of **checking data quality early** in any data analysis project!

