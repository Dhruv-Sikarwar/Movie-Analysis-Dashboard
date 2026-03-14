🎬 Movie Industry Analysis Dashboard
📊 Project Overview

This project analyzes movie industry data to identify factors influencing box office success. The analysis focuses on understanding the relationship between genres, directors, ratings, budgets, and box-office collections to help movie production houses make better investment decisions.

The dataset contains movie records from 2016–2020 with over 5200 rows and 12 columns, including information such as title, genre, budget, box office revenue, director, and release date.

🎯 Problem Statement

A movie production house wants to determine:

1.) Which genres generate the highest profit ?
2.)Which directors produce the most successful movies ?
3.)Whether higher ratings lead to higher box-office collection ?

The relationship between movie budget and revenue

🎯 Project Goals :-

1.) Perform data cleaning and standardization to ensure accurate analysis.

2.) Conduct exploratory data analysis (EDA) to discover patterns in movie performance.

3.) Generate data-driven insights and recommendations for future movie investments.

🧹 Data Cleaning & Preprocessing :-

The following preprocessing steps were performed:

-- Standardized Budget and Box Office columns by removing $, M, and commas.
-- Converted Release Date column into datetime format.
-- Removed 200 duplicate records.
-- Handled missing values using group-based averages.

Created new columns:

* Release_Year
* ROI
* Profit
* Profit_Status

📈 Key Insights :-
Genre Analysis

~ Action, Thriller, and Romance genres generate higher profits.
~ Drama movies, despite good ratings, generate comparatively lower revenue.
~ Director Analysis
~ Emily Stone is the most profitable director based on total profit generated.
~ She has directed 842 movies, primarily in the Action genre, which shows high profitability.

💡 Recommendations :-

-- Production houses should focus on high-performing genres like Action and Thriller.
-- Collaborating with experienced directors with strong revenue history can increase profitability.
-- Strategic budget allocation based on genre performance can improve ROI for future films.

🛠 Tools & Technologies :-

Python ( Numpy,Pandas,Matplotlib / Seaborn)
Power BI
Data Cleaning & Exploratory Data Analysis

📁 Dataset

Source: Kaggle
Dataset Size: 5200 rows × 12 columns
## 📂 Additional Resources

- 📊 ##**Project Presentation:** (Movies Analytics.pptx)
- 📈 ##**Dashboard File:** Power BI Dashboard (.pbix)

Dhruv Sikarwar
