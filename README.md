# Personal Health Metrics Analysis

## Overview
This project analyzes a daily panel dataset of personal health and activity metrics to study behavioral patterns, evaluate lifestyle factors, and develop predictive models for future health trends. The dataset spans three to four months of continuous daily tracking and includes nutrition, exercise, sleep, mood, cardiovascular performance and qualitative notes.

The goal is to build an end to end workflow that incorporates data cleaning, exploratory analysis, database design, feature engineering, modeling and interpretation.

## Objectives
- Create a structured and reproducible dataset suitable for analysis and long term monitoring  
- Design a relational database schema that organizes the wide table into focused views of nutrition, activity, cardiovascular metrics and lifestyle measures  
- Perform exploratory data analysis to identify trends and relationships among behaviors, workouts and physiological responses  
- Develop baseline predictive models for short term health outcomes using historical data  
- Compare performance across classical machine learning models and time based approaches  
- Establish a foundation for long term trend forecasting and personalized behavior insights  

## Data Description
Daily measurements include nutrition, sleep, subjective metrics and workout details. Columns include:

- Calorie Intake  
- Cheat Day (0 or 1)  
- Sleep (hours estimated)  
- Mood (b or a)  
- Physicality (b or a)  
- Workout Type  
- Duration (minutes)  
- Distance (meters)  
- Split (500 meter time per minute)  
- Stroke Rate (per minute)  
- Average Watts  
- Kettlebell Weight (kg)  
- Sets Completed  
- BPM (average heart rate)  
- Peak Heart Rate  
- Calories Burned  
- Daily Notes  

## Planned Work

### Data Engineering
- Clean and validate the dataset  
- Create a relational schema separating nutrition, workouts, cardiovascular metrics and subjective well being  
- Build ingestion scripts and documentation for future data updates  

### Exploratory Analysis
- Study correlations among workout type, intensity, sleep and subjective ratings  
- Visualize performance trends for rowing, kettlebell training and mobility  
- Analyze how lifestyle choices influence recovery and energy  

### Modeling
- Train predictive models for near term outcomes such as next day performance, mood or calorie burn  
- Compare linear models, tree based models and time dependent approaches  
- Build evaluation metrics and visualizations for interpretability  

## Future Extensions
- Integrate wearable device data  
- Add more detailed tagging for training sessions  
- Develop a dashboard for progress monitoring  
- Expand to long term forecasting of performance and recovery  

## Author
Addison DeSalvo  
Johns Hopkins University, M S Data Science
