# Will-Rettig-DA-401-Final-Project
This repository includes all files related to the final project of DA401 for Will Rettig.

# Introduction
This project explores whether arm injuries, specifically injuries to the UCL, can be prevented or predicted through analysis of various data points and systems that expose indicators of weakness or potential injuries.
It integrates NewtForce, ArmCare, Baseball Savant, Tommy John Surgery, and Lahman baseball data to investigate upper and lower body statistics and biomechanical metrics as predictors of arm stress.

# Summary of Files
DA401-Final-Project:

EarlyResults.Rmd -- Main analysis notebook

FirstDraftData.Rmd -- Main markdown file for this project

merged_data.csv -- NewtForce merged dataset

ArmCareApp.csv -- ArmCare app data

NF Data CSVs/ -- Raw session CSVs

NewtForce_Players_Info -- a smaller data set that includes individual player metrics and intanglibles

TJ_Surgery_List.csv -- data on Tommy John surgeries in professional and college baseball

PitchersFullBaseballSavant.csv -- includes all Baseball Savant metrics and statistics

Baseball_Savant_BMI_Included.csv -- full MLB CSV file with added variables and merged from Lahman Baseball

README.md -- Documentation

Predicting Arm Injury Risk in Baseball Pitchers Using Biomechanical and Strength Metrics.docx -- Early Results File

# Methods
Time Series Visualization -- average acceleration impulse (peak ground force) over time  

Lasso Regression -- variables predicting whether Tommy John surgery can be predicted with key variables  

Bivariate Scatterplots -- show relationships between BMI and peak and average fastball velocities

Correlation Heatmap -- summarizing variable relationships

# Data
NewtForce Mound

ArmCare App

Baseball Savant

Tommy John Surgery

Lahman Baseball Data

# Reproducing Code
1. Clone/download repo

2. Open FirstDraftData.rmd in RStudio

3. Ensure CSVs are in the same directory

4. Install applicable packages

5. Run all code chunks sequentially

6. Read code comments where available

# Future Work
-- Integrate FlexPro Grip data and more ArmCare App data

-- Incorporate stride length data for MLB pitchers

-- Greater N for Alpha Baseball athletes

-- Increase sample size for statistical significance

# Will Rettig 2025 Denison Data Analytics
