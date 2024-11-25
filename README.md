# Hybrid Audience Measurement and Media Analytics Platform

## Overview
This project focuses on building a machine learning-based system to integrate panel-based and census-level data for audience measurement. The dataset provided simulates real-world conditions with demographic, behavioral, and engagement metrics for analysis and modeling.

## Dataset Description
The dataset includes 2,000 rows and multiple columns with missing values, outliers, and imbalances to replicate the challenges of real-world data. It combines metrics from various advertising platforms, devices, and demographic groups.

## Columns
User_ID: Unique identifier for each user.
Age: Age of the user (18-65 years). Contains some missing values.
Gender: Gender of the user (Male, Female, Other).
Location: User's location type (Urban, Suburban, Rural).
Device_Type: Type of device used (Mobile, Desktop, Tablet).
Ad_Platform: Platform where the advertisement was viewed (TV, Digital, Social Media, Streaming).
Viewing_Hours: Number of hours spent viewing content. Contains extreme outliers.
Clicks: Number of ad clicks (Poisson distributed).
Purchase_Made: Target variable indicating whether a purchase was made (Yes/No, imbalanced).
Income: Annual income of the user (in USD). Contains missing values and extreme outliers.
Ad_Spent: Amount spent on ads viewed by the user (in USD).
Demographic_Group: User's demographic group (A, B, C, D).
Frequency: Number of times the ad was shown to the user.
Engagement_Score: Composite score (0-100) representing user engagement. Contains missing values.
Target Column
Purchase_Made: This is the target variable indicating whether a purchase was made ("Yes") or not ("No").
Features
Realism: Includes missing values, outliers, and data imbalances.
Diversity: Simulates cross-platform audience behavior and engagement metrics.
Scalability: Designed to test preprocessing, feature engineering, and machine learning models.

## Usage
Data Cleaning: Handle missing values, outliers, and inconsistencies.
Feature Engineering: Create hybrid features combining panel and census-level data.
Modeling: Build classification models to predict Purchase_Made.
Evaluation: Use metrics like accuracy, precision, recall, and AUC for performance analysis.

## Files
Synthetic_Hybrid_Audience_Data.csv: The synthetic dataset.
README_Hybrid_Audience_Measurement_Project.md: This documentation.

## Notes
This project is suitable for practicing real-world data preprocessing and developing machine learning pipelines. It aims to provide insights into audience behavior across platforms and optimize ad performance.

