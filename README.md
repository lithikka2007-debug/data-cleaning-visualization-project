# data-cleaning-visualization-project
A Python project for cleaning, processing, analyzing, and visualizing student performance data using Pandas, Matplotlib, and Seaborn.
# Student Performance Data Cleaning & Visualization

## About the Project

This project demonstrates data cleaning, analysis, and visualization using Python.

The dataset contains student information such as:

- Gender
- Study Hours
- Attendance
- Math Score
- Physics Score
- Computer Score

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning

The following data-cleaning techniques were used:

1. Checked for missing values
2. Filled missing numerical values using the median
3. Removed duplicate records
4. Detected and removed outliers using the IQR method
5. Saved the cleaned dataset

## Data Visualization

The project creates the following visualizations:

1. Distribution of Study Hours
2. Average Score by Subject
3. Study Hours vs Math Score
4. Attendance vs Average Score
5. Correlation Heatmap

## Key Findings

- Students who study more hours generally tend to achieve higher scores.
- Attendance has a positive relationship with student performance.
- Data cleaning improves the quality and reliability of analysis.
- Visualizations make patterns in the dataset easier to understand.

## How to Run

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn