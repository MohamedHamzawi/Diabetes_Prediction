# Diabetes Prediction using Support Vector Machine

This project demonstrates the development of a diabetes prediction model using a Support Vector Machine (SVM) classifier. The model is trained on a dataset containing various health indicators to predict whether a person is likely to be diabetic.

## Dataset

The dataset used in this project is `diabetes.csv`. It contains the following columns:

*   `Pregnancies`: Number of times pregnant
*   `Glucose`: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
*   `BloodPressure`: Diastolic blood pressure (mm Hg)
*   `SkinThickness`: Triceps skin fold thickness (mm)
*   `Insulin`: 2-Hour serum insulin (mu U/ml)
*   `BMI`: Body mass index (weight in kg/(height in m)^2)
*   `DiabetesPedigreeFunction`: Diabetes pedigree function
*   `Age`: Age (years)
*   `Outcome`: Class variable (0: non-diabetic, 1: diabetic)

## Project Steps

The project follows these steps:

1.  **Importing Dependencies**: Necessary libraries for data manipulation, model building, and evaluation are imported.
2.  **Data Collection and Analysis**: The `diabetes.csv` dataset is loaded and explored to understand its structure and basic statistics.
3.  **Data Standardization**: The features are standardized using `StandardScaler` to ensure that all features have a similar range of values, which is important for SVM.
4.  **Train-Test Split**: The dataset is split into training and testing sets to evaluate the model's performance on unseen data.
5.  **Training the Model**: A Support Vector Machine classifier with a linear kernel is trained on the standardized training data.
6.  **Model Evaluation**: The accuracy of the trained model is evaluated on both the training and testing datasets.
7.  **Making a Predictive System**: A function is created to take new input data, standardize it, and use the trained model to predict the outcome (diabetic or not).

## How to Run

1.  Clone this repository.
2.  Make sure you have the necessary libraries installed (numpy, pandas, scikit-learn).
3.  Ensure the `diabetes.csv` file is in the correct directory or update the file path in the code.
4.  Run the Python script or Jupyter Notebook containing the code.

## Results

The model's accuracy on the training data is approximately 77 % and on the testing data is approximately 78 %.

## Future Improvements

*   Explore other machine learning algorithms.
*   Perform more extensive feature engineering.
*   Tune the hyperparameters of the SVM model for better performance.
*   Implement cross-validation for more robust evaluation.
