# Churn-modelling-prediction

Understanding the Problem

Goal: Predict if a customer will leave (churn) or stay.

Target Variable: Exited (1 = churn, 0 = retained).

Data Preprocessing

Remove unnecessary columns (RowNumber, CustomerId, Surname).

Encode categorical variables (Gender, Geography).

Split data into features (X) and target (y).

Standardize numerical features for better model performance.

Model Training

Use Random Forest Classifier as a baseline model.

Train the model on the preprocessed data.

Model Evaluation

Make predictions on test data.

Measure accuracy and classification performance.
