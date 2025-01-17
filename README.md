# Linear Regression - Auto MPG Prediction

This project focuses on predicting the miles per gallon (MPG) of vehicles using a dataset that includes various features like the number of cylinders, horsepower, weight, acceleration, and more. The goal is to create a linear regression model that accurately predicts the MPG of a vehicle based on these features.

## Dataset

The dataset used in this project is the **Auto MPG** dataset, which includes information about various car models and their attributes. The dataset has the following columns:

- **mpg**: Miles per gallon (target variable)
- **cylinders**: Number of cylinders
- **displacement**: Engine displacement (in cubic inches)
- **horsepower**: Horsepower of the car
- **weight**: Weight of the car (in pounds)
- **acceleration**: Acceleration (in m/s²)
- **model year**: Year the car was manufactured
- **origin**: The origin of the car (1: USA, 2: Europe, 3: Japan)
- **car name**: Name of the car

## Objective

The main objective of this project is to:

- Build a **linear regression model** to predict the MPG of a car.
- Explore the relationship between different features and the target variable (MPG).
- Evaluate the model using metrics like **mean squared error (MSE)** and **R² score**.

## Steps Involved

1. **Data Preprocessing**:
   - Import the dataset and inspect for any missing values.
   - Encode categorical features if necessary (e.g., the "origin" column).
   - Normalize numerical features to bring them onto a similar scale.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize relationships between the features and the target variable.
   - Analyze correlations between different features and the target variable (MPG).

3. **Modeling**:
   - Split the data into training and testing sets.
   - Implement linear regression using the **scikit-learn** library.
   - Train the model on the training data and evaluate it on the test set.

4. **Evaluation**:
   - Calculate the R² score and Mean Squared Error (MSE) to evaluate model performance.

## Requirements

To run this project, you'll need the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Conclusion
This project demonstrates how linear regression can be applied to predict the MPG of a car based on its features. The model can be improved further by exploring more advanced techniques or by using different algorithms.
