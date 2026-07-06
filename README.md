# Exploratory Data Analysis (EDA) on Titanic Dataset

## Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The objective is to analyze the dataset through statistical summaries and visualizations to identify patterns, trends, and relationships that influenced passenger survival.

## Objective
- Understand the structure of the dataset.
- Perform data cleaning and preprocessing.
- Explore data using descriptive statistics.
- Visualize relationships between different features.
- Extract meaningful insights from the dataset.

## Tools & Technologies
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Dataset
- **Dataset:** Titanic Dataset (`train.csv`)
- **Records:** 891 passengers
- **Features:** 12 columns including passenger details, ticket information, fare, class, age, gender, and survival status.

## Steps Performed
- Imported and explored the dataset using:
  - `head()`
  - `info()`
  - `describe()`
  - `value_counts()`
- Identified missing values.
- Filled missing values in:
  - **Age** using the median.
  - **Embarked** using the mode.
- Removed the **Cabin** column due to a high percentage of missing values.
- Generated various visualizations:
  - Histograms
  - Count plots
  - Box plots
  - Scatter plots
  - Pair plot
  - Correlation Heatmap
- Calculated summary statistics including:
  - Total passengers
  - Survival rate
  - Average age
  - Average fare

## Key Findings
- The dataset contains **891 passengers**.
- The overall survival rate is **38.38%**.
- Female passengers had a significantly higher survival rate than male passengers.
- First-class passengers had better survival chances compared to second and third class.
- Most passengers were between **20–40 years** of age.
- Fare distribution is highly right-skewed with several outliers.
- Passenger class and fare showed stronger relationships with survival than age.
- Correlation analysis indicated that gender and passenger class had the greatest influence on survival.

## Learning Outcomes
- Performed real-world exploratory data analysis using Python.
- Learned data preprocessing and handling missing values.
- Created meaningful visualizations using Matplotlib and Seaborn.
- Identified trends, relationships, and anomalies within the dataset.
- Improved understanding of statistical analysis and data visualization techniques.

## Project Structure
```
├── Titanic_EDA.ipynb
├── Titanic_EDA_Report.pdf
├── train.csv
└── README.md
```

## Author
**Ria Mehrotra**

**Elevate Labs – Data Analytics Internship**

**Task 5: Exploratory Data Analysis (EDA)**
