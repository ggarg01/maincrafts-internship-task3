# Titanic Dataset Exploratory Data Analysis (EDA)

### Maincrafts Data Science & Analytics Internship - task 3

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The task includes data cleaning, feature engineering, group-wise analysis, and data visualization to identify patterns and relationships affecting passenger survival.

## Tasks Completed

### Data Exploration and Cleaning

* Loaded the dataset using Pandas.
* Examined dataset structure, columns, and missing values.
* Filled missing values in the Age column using the mean.
* Filled missing values in the Embarked column using the mode.
* Removed the Cabin column due to a large number of missing values.
* Created a new Family Size feature using the SibSp and Parch columns.

### Data Analysis

* Calculated survival rates by age group.
* Analyzed survival rates by embarkation port.
* Examined the relationship between family size and survival.
* Explored correlations between numerical features.

### Visualizations

* Histogram of passenger age distribution.
* Bar chart of survival rate by age group.
* Bar chart of survival rate by embarkation port.
* Bar chart of survival rate by family size.
* Correlation heatmap of numerical features.

## Key Findings

* Children generally had higher survival rates than senior passengers.
* Survival rates varied across different embarkation ports.
* Passengers travelling with small families generally had higher survival rates than those travelling alone or in very large families.
* The majority of passengers belonged to the young adult age group.
* The correlation heatmap highlighted relationships between passenger attributes and survival.

## Files Included

* task3_titanic_EDA_analysis.ipynb – Jupyter Notebook containing the complete exploratory data analysis and visualizations.
* Titanic-Dataset.csv – Titanic dataset used for the analysis.

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook (VS Code)
