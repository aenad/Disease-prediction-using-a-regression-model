# Disease Prediction Using a Regression Model
the first project in Data Mining course

## Project Overview

This project aims to predict the likelihood of various diseases using a regression model. The dataset used in this project contains several features that help us model the relationship between input health indicators and the target disease probabilities. The model leverages regression techniques to analyze the relationships and generate predictions.

The primary goal of this project is to use data mining and regression techniques to identify patterns and predict disease presence based on available health data. The project provides a practical example of using machine learning in healthcare, demonstrating how data-driven insights can assist in disease risk assessment.

## Data and Methods

### Dataset
The dataset used in this project includes health indicators like age, blood pressure, cholesterol level, glucose levels, and other clinical measurements. Each row represents a patient, and the target variable is the probability of having a certain disease.

### Methodology
- **Data Preprocessing**: The data is first cleaned to handle missing values, standardize numerical features, and encode categorical values.
- **Feature Selection**: Important features that significantly influence disease prediction are selected using feature importance metrics.
- **Model Selection**: A regression model is used to predict disease probability. We experimented with different models, including linear regression, ridge regression, and Lasso regression, and evaluated them to determine the best fit.
- **Evaluation Metrics**: Metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared are used to evaluate the performance of the models.

## Results
The final regression model showed promising results, with an R-squared value of approximately X. The model effectively captured the relationships between health indicators and disease probability, making it a useful tool for preliminary risk assessments.

- **Key Insights**:
  - Blood pressure and cholesterol level were found to be the most significant predictors of disease risk.
  - The model performed best when hyperparameter tuning was applied to the ridge regression variant.

## Installation and Usage

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/disease-prediction-regression.git
   ```
2. **Install required dependencies**:
   ```
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   Open the `Disease prediction using a regression model.ipynb` notebook to explore the dataset and model.

## Conclusion
This project illustrates the potential of regression models in the healthcare domain for disease prediction. By analyzing different clinical features, we can derive meaningful insights and support medical professionals in their decision-making processes.

Feel free to contribute, raise issues, or fork this project to expand its capabilities!
