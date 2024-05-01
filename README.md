
# Mileage Prediction

## Objective

The objective of this project is to predict the mileage of vehicles based on various features using machine learning techniques.

## Data Source

The dataset used for this project is sourced from [MPG Dataset](https://github.com/YBI-Foundation/Dataset/raw/main/MPG.csv).

## Steps

1. **Importing Libraries**: The necessary libraries such as pandas, matplotlib, seaborn are imported for data manipulation and visualization.

2. **Importing Data**: The dataset is imported using pandas' `read_csv()` function.

3. **Exploratory Data Analysis (EDA)**:
   - Initial exploration of the dataset using `head()` and `info()` functions.
   - Summary statistics of the dataset using `describe()` function.
   - Visualization of the relationship between acceleration and mileage using seaborn's `regplot()`.

4. **Data Preprocessing**:
   - Handling missing values by dropping rows with missing values.
   - Correlation analysis to understand the relationship between variables.

5. **Feature Selection**:
   - Selecting relevant features (`displacement`, `horsepower`, `weight`, `acceleration`) for mileage prediction.

6. **Train-Test Split**:
   - Splitting the dataset into training and testing sets using `train_test_split()`.

7. **Model Building**:
   - Utilizing Linear Regression model for predicting mileage.
   - Training the model on the training dataset using `fit()` method.

8. **Model Evaluation**:
   - Predicting mileage on the test dataset using `predict()` method.
   - Evaluating the model's performance using R-squared score and Mean Absolute Percentage Error.

9. **Sample Prediction**:
   - Providing a sample input (`displacement`, `horsepower`, `weight`, `acceleration`) to predict mileage for a vehicle.

## Model Performance

- **R-squared Score**: The model achieves an R-squared score of 0.87, indicating 87% variance explained by the features.
- **Mean Absolute Percentage Error (MAPE)**: The MAPE of the model is 13%, indicating an average error of 13% in predicting mileage.

