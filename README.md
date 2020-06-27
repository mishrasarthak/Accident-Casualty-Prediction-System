# Accident-Casualty-Prediction-System
This project predicts the Accident Casualty of an Individual from a given  dataset which includes weather conditions , temperature , lighting conditions, etc. The approach for prediction of casualty severity has two steps: a. Cluster the data using agglomerative clustering algorithm,  b. Prediction using lasso lars regression model.

=>The approach for prediction of casualty severity has two steps:

a. Cluster the data using agglomerative clustering algorithm

Cluster 0 Rules:
Road Surface is in average 15.31% smaller : mean of 1.10 against 1.30 globally
Casualty Severity is in average 11.63% smaller : mean of 1.00 against 1.13 globally
Weather Conditions is in average 15.13% smaller : mean of 1.04 against 1.22 globally

Cluster 1 Rules:
Casualty Severity is in average 80.57% greater : mean of 2.05 against 1.13 globally
Type of Vehicle is in average 12.33% smaller : mean of 3.32 against 3.79 globally
Number of Vehicles is in average 14.70% smaller : mean of 1.67 against 1.95 globally

Cluster 2 Rules:
Road Surface is in average 57.93% greater : mean of 2.06 against 1.30 globally
Weather Conditions is in average 61.05% greater : mean of 1.97 against 1.22 globally
Casualty Severity is in average 10.32% smaller : mean of 1.02 against 1.13 globally

