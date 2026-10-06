# Titanic Exploratory Data Analysis (EDA)

## Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand passenger characteristics and identify factors associated with survival.

## Dataset
The analysis uses the Titanic `train.csv` dataset containing passenger information such as:

- Age
- Gender
- Passenger Class
- Fare
- Embarkation Port
- Survival Status

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Data Cleaning
- Handled missing values in the Age column using the median.
- Filled missing Embarked values using the mode.
- Removed the Cabin column because it contained a large number of missing values.

## Exploratory Data Analysis
The analysis includes:

- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution
- Fare Distribution
- Survival by Embarkation Port
- Age Distribution by Survival
- Correlation Heatmap
- Survival Rate by Gender
- Survival Rate by Passenger Class
- Summary Statistics

## Key Insights
- Female passengers had a much higher survival rate than male passengers.
- First-class passengers had a higher survival rate than second and third-class passengers.
- Third-class passengers had the highest number of non-survivors.
- Most passengers were between approximately 20 and 40 years old.
- Fare distribution was highly right-skewed.
- Most passengers embarked from Southampton (S).
- Passenger class and fare showed noticeable relationships with survival.

## Files
- `Task_2_Titanic_EDA.ipynb` - Complete EDA notebook
- `train.csv` - Titanic dataset

## Author
Rizwan Ali Khoso
