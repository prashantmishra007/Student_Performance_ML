# Student Performance Prediction System

An end-to-end Machine Learning project developed as part of the AI/ML Internship. This system analyzes demographic, socioeconomic, and academic attributes to predict student examination performance.

## Project Overview
- **Dataset:** `StudentsPerformance.csv` (1,000 records)
- **Target Variable:** `math_score`
- **Model:** Multiple Linear Regression (Ordinary Least Squares)

## Workflow & Methodology
1. **Data Understanding & Cleaning:** Inspected data types and confirmed 0 missing values across all columns.
2. **Feature Engineering:** Calculated `total_score` and `average_score`; applied One-Hot Encoding on categorical attributes.
3. **Exploratory Data Analysis (EDA):** Visualized distributions, score correlations, and group-wise performance variations.
4. **Model Training & Evaluation:** Performed an 80/20 train-test split.
   - Mean Absolute Error (MAE): **7.09**
   - Root Mean Squared Error (RMSE): **9.20**
   - R-squared ($R^2$): **0.5962**
5. **Key Drivers:** Standard lunch access and parental higher education positively correlate with higher scores, whereas skipping the test prep course significantly reduces performance.

## Repository Structure