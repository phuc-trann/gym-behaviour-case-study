# Gym Member Behaviour EDA Case Study

This report is based on the Kaggle dataset: *Gym Members Exercise Dataset*, available under this [link](https://www.kaggle.com/datasets/valakhorasani/gym-members-exercise-dataset).

This report details the analysis of the gym dataset, containing exercise tracking information for 973 gym member sessions. The primary goal was to understand the factors influencing workout outcomes, explore behavioral patterns, and assess the predictability of key metrics using various modeling techniques, including linear models and CatBoost gradient boosting.

Key findings reveal that workout duration and average heart rate (intensity) are the strongest drivers of calories burned, alongside member weight and workout type. Member experience level significantly correlates with increased workout frequency and duration. We observed expected gender differences in body composition metrics (Fat % and BMI) within this population.

Linear regression models and CatBoost demonstrated high predictive accuracy for calories burned, with detailed performance metrics presented in the Evaluation section. CatBoost potentially offered slightly better performance by handling feature interactions and non-linearities inherently. The features identified during exploratory analysis proved crucial across models.
