# Titanic Data Cleaning & Passenger Analysis

## Project Overview

This project focuses on cleaning and analyzing the Titanic dataset to understand passenger survival patterns. The dataset was processed using Python and various data analysis libraries. Exploratory Data Analysis (EDA) was performed to identify trends and factors affecting passenger survival.

## Objective

To clean the Titanic dataset and analyze passenger survival trends based on factors such as age, gender, and passenger class.

## Dataset

- Dataset: Titanic Dataset
- Source: Kaggle
- Format: CSV

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Data Cleaning

- Loaded the dataset using Pandas.
- Checked for missing values.
- Filled missing values in Age and Embarked columns.
- Removed the Cabin column due to excessive missing values.
- Checked and removed duplicate records.
- Identified and treated outliers using boxplots and the IQR method.

## Statistical Analysis

- Calculated descriptive statistics.
- Analyzed age and fare distributions.
- Calculated passenger survival rates.
- Examined relationships between different passenger attributes.

## Grouping Analysis

- Grouped passengers by gender.
- Grouped passengers by passenger class.
- Compared survival rates among different groups.
- Calculated average age by passenger class.

## Visualizations Created

- Survival Count Plot
- Gender Distribution Plot
- Passenger Class Distribution Plot
- Age Histogram
- Age Boxplot

## Key Observations

1. Female passengers had a significantly higher survival rate than male passengers.
2. First-class passengers were more likely to survive than second- and third-class passengers.
3. Younger passengers generally had better chances of survival.
4. Most passengers belonged to the young and middle-aged age groups.
5. Passenger class and gender were major factors influencing survival.

## Conclusion

The analysis revealed that survival on the Titanic was strongly influenced by gender and passenger class. Female passengers and first-class travelers had the highest survival rates. This project demonstrates the importance of data cleaning, statistical analysis, and visualization in extracting meaningful insights from real-world datasets.

## Repository Structure

```
Titanic-Data-Cleaning-and-Passenger-Analysis/
│
├── Titanic_EDA.ipynb
├── train.csv
├── README.md
└── images/
```

## Author

 Lalithasri Amrutha.K
