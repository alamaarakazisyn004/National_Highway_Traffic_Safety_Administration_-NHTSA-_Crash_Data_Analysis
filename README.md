# Traffic Accident Pattern Analysis and Crash Severity Prediction using NHTSA Crash Data

--------------------------------------------------------------------------

# Project Overview

Road traffic accidents are a major public safety concern worldwide. Understanding accident patterns and identifying factors associated with severe crashes can help improve road safety planning and prevention strategies.

This project analyzes crash records from the National Highway Traffic Safety Administration (NHTSA) dataset to explore accident trends, geographic distributions, and demographic characteristics of crash victims. In addition to exploratory analysis, a baseline machine learning model is developed to predict crash severity based on various accident-related features.

----------------------------------------------------------------------------

# Project Objectives

1. Analyze traffic accident data to identify patterns related to time, location, and demographic factors.
2. Perform data cleaning and preprocessing to prepare the dataset for analysis.
3. Conduct exploratory data analysis (EDA) to understand crash trends.
4. Visualize accident patterns using meaningful charts and graphs.
5. Build a machine learning model to predict crash severity.
6. Evaluate model performance using standard classification metrics.

---------------------------------------------------------------------------

# Dataset Information

The dataset contains crash records including information such as:
  1. Geographic location (latitude and longitude)
  2. Collision date and time
  3. Victim age and gender
  4. Type of collision
  5. Street type
  6. Neighborhood and district information
  7. Fatality indicator (deceased)

These attributes allow analysis of both spatial and temporal accident patterns.

------------------------------------------------------------------------

# Tools and Technologies Used

1. Programming Language

Python

2. Libraries

Pandas – data manipulation and analysis
NumPy – numerical computation
Matplotlib – data visualization
Seaborn – statistical visualization
Scikit-learn – machine learning models and evaluation

----------------------------------------------------------------------------

# Project Workflow

1. Data Collection

The crash dataset was obtained from publicly available traffic safety data sources.

2. Data Cleaning

1) Removed duplicate records
2) Handled missing values
3) Filtered incomplete entries
4) Converted date and time columns to datetime format

3. Feature Engineering

Additional features were created including:
  1) Collision hour
  2) Collision month
  3) Day of the week

These features help identify time-based accident trends.

4. Exploratory Data Analysis

EDA was performed to understand:
  1) Age distribution of accident victims
  2) Frequency of accidents by time of day
  3) Gender distribution
  4) Collision type patterns
  5) Geographic distribution of accidents

5. Data Visualization

Multiple charts were generated to highlight patterns in accident data including:
          1) Histogram plots
          2) Count plots
          3) Geographic scatter plots
          4) Neighborhood accident comparisons

6. Machine Learning Model

A classification model was developed to predict whether a crash resulted in a fatality.

The following algorithms were used:

    1) Logistic Regression (baseline model)
    2) Random Forest Classifier

7. Model Evaluation

Model performance was evaluated using:
          1) Accuracy Score
          2) Confusion Matrix
          3) Classification Report

----------------------------------------------------------------------------

# Key Insights

1. Certain hours of the day show a higher concentration of accidents.
2. Specific neighborhoods report more crash incidents compared to others.
3. Age groups between young adults and middle-aged individuals appear frequently in accident records.
4. Some collision types are associated with higher fatality risk.

# Conclusion

The analysis demonstrates that traffic accident data can provide valuable insights into crash patterns and risk factors. By applying exploratory data analysis and machine learning techniques, it is possible to identify conditions that contribute to severe accidents. These insights can support data-driven decision making in road safety and traffic management.
