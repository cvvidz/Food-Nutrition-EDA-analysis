# Food Nutrition EDA Project

# Overview
This project performs an Exploratory Data Analysis (EDA) ,Food Display Table (2011 entries, 26 columns)
The goal is to understand how different food groups and nutrients contribute to total calories and discover patterns among solid fats, added sugars and overall nutrient composition.

# Tools Used
Python(Pandas, NumPy, Seaborn, Matplotlib)
Google Colab 
GitHub for version control

# Dataset
Source: https://www.kaggle.com/datasets/thebumpkin/food-nutrition-data-on-2000-foods 
Rows: 2011 , Columns:26  
Key Fields: Display_Name, Calories, Solid_Fats, Added_Sugars, Vegetables, Fruits, Meats  


# Data Cleaning Steps
Understood the data
Normalized column names   
Verified numeric types and handled string conversion errors  
Checked missingness - 0 missing values.  
Grouped variables into food groups and energy components for analysis.

# Key Analyses
Distribution of Calories –  mean = 154 kcal per portion.  
Correlation Analysis – solid_fats (r ≈ 0.88) and saturated_fats strongly drive calories.  
Food-Group Comparison – grains & meats contribute the largest portion share.  
Calories vs Solid Fats – clear positive trend across foods.


# Insights
Foods rich in solid fats/saturated fats are calorie-dense.  
Added sugars show moderate correlation with calories.  
Vegetables and fruits add volume but low energy.  


