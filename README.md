Diabetes Prediction

The project uses logistic regression to predict whether a patient is diabetic or not. This is based off of diagnostic health features found in the Pima Indians Diabetes dataset.


Process:
- Cleaned invalid values in "Glucose", "BMI", "Insulin", "BloodPressure", and "SkinThickness"
- Replaced 0s with the median where applicable.
- Scaled numerical features by using MinMaxScaler.
- Trained a logistic regression model using scikit-learn.
- Successfully achieved **78.81% accuracy** on the test set.

Dataset:
  Pima Indians Diabetes Dataset — [Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
