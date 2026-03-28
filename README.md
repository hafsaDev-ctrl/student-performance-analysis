# Student Performance Analysis

## Introduction
This project was completed as part of the Data Science Bootcamp 2026. The goal was to analyze a messy dataset of student records and build a model to predict final scores. The work covers the full data science pipeline: cleaning, exploration, feature engineering, modeling, and evaluation.

## Dataset
The dataset contains 205 rows and 14 columns. It includes information about student demographics, attendance, study habits, and exam scores. The raw data had several issues such as inconsistent text formatting, missing values, wrong data types, and impossible values that needed to be fixed.

## Steps Followed
- **Data Cleaning**: Fixed casing in names and gender, corrected department labels, converted age to numeric, handled missing values, removed duplicates, and corrected impossible values in attendance and scores.
- **Exploratory Data Analysis (EDA)**: Created histograms, scatter plots, heatmaps, boxplots, and countplots to understand distributions and relationships. Each visualization was interpreted to highlight key findings.
- **Feature Engineering**: Added new features like `Total_Academic` (combined scores) and `Attendance_Category` (Low, Medium, High).
- **Model Building**: Used a preprocessing pipeline with encoding and scaling, followed by a Linear Regression model.
- **Evaluation**: Measured performance using MAE, RMSE, and R². Compared actual vs predicted scores and reviewed coefficients.

## Results
- **MAE:** 2.45  
- **RMSE:** 3.27  
- **R²:** 0.59  

These results show that the model explains about 59% of the variation in student scores. Predictions are usually within 2–3 points of the actual score.

## Insights
- Students with higher attendance and more study hours tend to achieve better final scores.
- Midterm performance is strongly linked to final exam results.
- Departments show differences in average performance, suggesting variation in teaching or student backgrounds.

## Conclusion
The project demonstrates a complete workflow from raw data to prediction. While the Linear Regression model provides a good baseline, accuracy could be improved by adding more features (such as family background or internet speed) and testing advanced models like Random Forest or XGBoost. Overall, this project helped me practice the full data science pipeline and understand the factors influencing student performance.

---
**Deadline:** March 27, 2026  
**Submitted by:** Hafsa Mazhar
