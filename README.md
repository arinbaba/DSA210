DSA 210 Project Report: Magnesium Intake and Fitness Performance Analysis
1. Introduction

This report presents the results of a 60-day data science project investigating the relationship between nutritional supplementation (especially magnesium), sleep quality, and fitness performance. Using synthetically generated but realistic data derived from wearable devices and training logs, the goal was to determine how various supplement intakes and behavioral metrics affect physical performance and sleep outcomes.

2. Project Objectives

The main objectives of the project were:
- To analyze how daily magnesium intake influences total sleep duration and sleep stages.
- To assess whether sleep quality and supplement intake impact strength performance metrics such as bench press, squat, lat pulldown, and dumbbell press (total weight lifted).
- To use exploratory data analysis (EDA), statistical testing, and machine learning models to uncover meaningful patterns and predictive relationships.

3. Dataset Description

The dataset includes the following features tracked over 60 days:
- Sleep Metrics: Total Sleep Hours, REM, Deep, and Light Sleep durations.
- Supplement Intake: Magnesium (mg), Glutamine (g), L-Carnitine (g), Vitamin D (IU), Creatine (g).
- Fitness Performance: Total daily training volume (kg) for Bench Press, Squat, Lat Pulldown, and Dumbbell Press (calculated as sets * reps * weight).
- Other: Body weight (in kg), daily step count, and calorie/macronutrient intake.

4. Exploratory Data Analysis (EDA)

- Correlation heatmaps showed a moderate relationship between magnesium intake and REM sleep duration.
- Scatter plots and boxplots were used to visualize outliers and variation across supplement and performance variables.
- Sleep Score and Sleep Duration were more influenced by REM and Light sleep stages than Deep sleep.
- Training volume for strength movements had a loose positive association with sleep hours and magnesium intake.

5. Hypothesis Testing

We performed Pearson correlation tests and t-tests with α = 0.05.
Key tested hypotheses included:
- H₀: No correlation between Magnesium and REM Sleep → Rejected.
- H₀: No correlation between Sleep Hours and Total Training Volume → Failed to reject (weak correlation).
- H₀: No difference in training output between high and low magnesium intake days → Borderline significance.

6. Machine Learning Models Used

We tested multiple regression models to predict strength performance and sleep quality:
- Linear Regression (for predicting Bench Press volume from sleep and supplement data).
- Ridge and Lasso Regression (for overfitting control and variable selection).
- Random Forest Regressor (for better handling of non-linear relationships).
- Polynomial Features were also explored for capturing non-linearities.
Model performance was evaluated using R² score and RMSE.

7. Visual Insights from PowerPoint Slides

We included the following visualizations in our final presentation:
- Heatmaps of feature correlations.
- Scatter plots between magnesium and sleep stages.
- Regression plots showing model predictions vs. actual values.
- Bar charts of daily training volume trends.
- Pairplots of all numerical features.
These helped in drawing meaningful conclusions and communicating our findings clearly.

8. Conclusion

Magnesium intake was moderately correlated with improved REM sleep and slightly better overall sleep score. However, its effect on fitness performance was minimal, suggesting indirect benefits. Sleep quality was mildly associated with higher training volumes, but the results were not uniformly strong across all movements.
Future iterations could integrate heart rate variability, hydration, and stress data to refine the models further.




