# Traffic Accident Pattern Analysis and Crash Severity Prediction
# Project Overview

Road traffic accidents remain a significant public safety issue across many regions. Analyzing accident data can help identify patterns that contribute to severe crashes and support data-driven decision making for improving road safety.

This project focuses on analyzing traffic accident records from the National Highway Traffic Safety Administration (NHTSA) crash dataset. The analysis explores accident patterns related to time, location, demographic characteristics, and collision types. In addition, a baseline machine learning model is developed to predict accident severity based on available features.

The project demonstrates the application of data preprocessing, exploratory data analysis, visualization, and machine learning techniques using Python.

# Project Objectives

1. Explore traffic accident data to identify accident trends and patterns
2. Perform data cleaning and preprocessing to prepare the dataset for analysis
3. Conduct exploratory data analysis to understand accident distribution
4. Visualize accident patterns using informative charts
5. Develop a machine learning model to predict crash severity
6. Evaluate model performance using classification metrics

# Dataset Description

The dataset contains records of traffic collisions including geographic, temporal, and demographic information.

Some key attributes included in the dataset:
1. unique_id – unique record identifier
2. latitude / longitude – geographic location of the crash
3. collision_date / collision_time – date and time of accident
4. death_date / death_time – time associated with fatality
5. age – age of the individual involved in the accident
6. sex – gender of the individual
7. collision_type – type of crash event
8. street_type – type of road where the accident occurred
9. analysis_neighborhood – neighborhood of the crash location
10. police_district – district where the accident was reported
11. supervisor_district – administrative district information
12. deceased – indicator representing fatal crash outcome

# Tools and Technologies
# Programming Language

Python

# Libraries Used

Pandas – data manipulation and preprocessing

NumPy – numerical computations

Matplotlib – data visualization

Seaborn – statistical data visualization

Scikit-learn – machine learning modeling and evaluation

# Project Workflow
1. Data Loading

The dataset was imported using the Pandas library. Initial exploration was performed to examine dataset size, column types, and missing values.

2. Data Cleaning

The following preprocessing steps were performed:

Removed duplicate records

Identified and handled missing values

Dropped rows containing null values in important columns such as:

  death_time
  collision_time
  age
  analysis_neighborhood
  supervisor_district
  data_as_of

Converted date and time columns into datetime format for analysis.

3. Feature Engineering

Additional features were created to analyze temporal accident trends:
    Collision hour
    Collision day of the week
    Collision month

These features help understand how accidents vary throughout different times.

4. Exploratory Data Analysis (EDA)

Exploratory analysis was conducted to identify patterns in accident occurrences.

The analysis focused on:
    Age distribution of accident victims
    Gender distribution
    Accident frequency by hour of the day
    Collision type distribution
    Neighborhood accident counts
    Geographic accident distribution using latitude and longitude

# Data Visualization

Several visualizations were created to better understand the dataset, including:
    Age distribution histogram
    Accidents by hour of the day
    Collision type frequency chart
    Gender distribution plot
    Neighborhood accident comparison
    Geographic crash location scatter plot

These visualizations help reveal important accident trends and patterns.

# Machine Learning Model

A classification model was developed to predict crash severity based on accident attributes.

Feature Variables

Examples of features used for prediction:

Age
Sex
Collision type
Street type
Collision hour
Collision month
Geographic coordinates

# Target Variable

deceased – indicates whether the accident resulted in a fatality.

# Models Implemented
# Logistic Regression
Used as a baseline classification model to predict crash severity.

# Random Forest Classifier
An ensemble machine learning model used to improve prediction performance by combining multiple decision trees.

#Model Evaluation
The models were evaluated using the following metrics:

Accuracy Score

Confusion Matrix

Classification Report

These metrics help measure the model's ability to correctly classify accident severity outcomes.

Key Insights

The analysis revealed several patterns in the accident dataset:

Certain hours of the day show higher accident frequency.

Some neighborhoods report more crashes than others.

Young and middle-aged individuals appear frequently in accident records.

Specific collision types may be associated with higher fatality risk.

These findings highlight how accident data can provide insights into traffic safety conditions.
