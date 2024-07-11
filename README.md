# Heart Disease Prediction with Machine Learning

* This repository explores the use of machine learning to predict heart disease risk.
* It analyzes the heart-1.csv dataset, which includes patient information and their heart disease status.

## Explanation of Each column:
1. age - age of the patient in years.
2. sex - gender of the patient. ( 0- female, 1 - male)
3. cp - chest pain type. this column likely represents diff categories or levels of chest pain experienced by the patient.
4. trestbps - resting blood pressure (in mm Hg) mesured at admission to the hospital
5. chol - serum cholestrol level (in mg/dl) at admission to the hospital.
6. fbs - fasting blood sugar level. this column likely indicates whether the patient had a fasting blood sugar level higher than 120mg/dl (1 for yes, 0 for no).
7. restecg- resting the electrocardiographic results. this column may represent different categories or levels of resting ECG results.
8. thalach - maximum heart rate achieved during the exercise test.
9. exang - exercise- induced angina (1 for yes, 0 for no). it indicates whether the patient experienced angina (chest pain or discomfort) during exercise.
10. oldpeak - st depression induced by exercise relative to rest. this a measure of how much the st segment of the ecg changes during exercise compared to test.
11. slope - the slope of the peak exercise st segment. this likely represents different categories or levels of the scope of st segment changes during exercise.
12. ca - the number of major vessels (0-3) coloured by fluoroscopy. this is often used as a measure of the number of the blood vessels with significant narrowing.
13. thal - a blood disorder called thalassemia (a categorical variable with different levels).
14. target - the target variable or the outcome you are trying to predict. in the context of heart disease prediction, this column typically indicates whether a patient has heart disease(1 for yes, 0 or no). 

## Key Features:

* Exploratory Data Analysis: Analyzes data distribution, correlations, and class imbalance.
* Machine Learning Models: Trains and evaluates Decision Tree, Random Forest, and Logistic Regression models.
* Performance Evaluation: Provides accuracy scores to assess model effectiveness.

## Further Exploration:

* Hyperparameter tuning for improved model performance.
* Experimentation with additional machine learning algorithms (SVMs, ensemble methods).
* Feature importance analysis to identify key factors in heart disease prediction.

  
This description effectively conveys the project's purpose, main functionalities, and potential for further exploration.
