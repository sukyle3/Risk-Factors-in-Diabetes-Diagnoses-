# Data

## Summary
This project uses a **sampled subset (n = 1,000)** from the CDC BRFSS 2015 diabetes indicators dataset (originally 70,692 responses).  
The goal is to predict whether an individual is diabetic or pre-diabetic using health, lifestyle, medical care, and demographic factors.

## Files
- Due to data sharing restrictions, this repository does **not** include the course-distributed sample (`Diabetes_S1.csv`).To reproduce the analysis, download the CDC BRFSS 2015 diabetes indicators dataset from UCI and create a compatible subset. A simple way is to filter to the 21 variables listed below and take a reproducible random sample of 1,000 rows (set a seed).

## Source
- UCI Machine Learning Repository: CDC Diabetes Health Indicators (BRFSS 2015)  
  UCI dataset: https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

## Variable documentation
The UCI page above contains the full variable definitions.  
The dataset includes **21 predictors** spanning comorbidities, health metrics, lifestyle, medical care access, and demographics.

## Notes for reproducibility
The SAS code expects a CSV with the standard column names used in the course dataset, including:
- Outcome: `Diabetes_binary` (0/1)
- Common predictors: `HighBP`, `HighChol`, `BMI`, `GenHlth`, `MentHlth`, `PhysHlth`, `DiffWalk`,
  `CholCheck`, `Smoker`, `PhysActivity`, `Fruits`, `Veggies`, `HvyAlcoholConsump`,
  `AnyHealthcare`, `NoDocbcCost`, `Sex`, `Age`, `Education`, `Income`,
  `Stroke`, `HeartDiseaseorAttack`



