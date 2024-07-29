# Mileage Prediction - Regression Analysis

## Overview

This project aims to predict city-cycle fuel consumption in miles per gallon (mpg) using various attributes of automobiles. The dataset used is a modified version of the one provided in the StatLib library, originally used in the 1983 American Statistical Association Exposition.

## Dataset Information

The dataset consists of 398 instances, each with 9 attributes. The original dataset had some instances with unknown values for the "mpg" attribute, which were removed for this analysis.

**Attribute Information:**
1. mpg: continuous
2. cylinders: multi-valued discrete
3. displacement: continuous
4. horsepower: continuous
5. weight: continuous
6. acceleration: continuous
7. model year: multi-valued discrete
8. origin: multi-valued discrete
9. car name: string (unique for each instance)

## Project Structure

The project follows these steps:

1. **Import Libraries**
2. **Import Data**
3. **Data Preprocessing**
4. **Data Visualization**
5. **Define Target Variable y and Feature X**
6. **Scaling Data**
7. **Train Test Split Data**
8. **Linear Regression Model**
9. **Predict Test Data**
10. **Model Accuracy**
11. **Polynomial Regression**
12. **Model Accuracy for Polynomial Regression**

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Instructions

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/th3varun/Mielage-Prediction-Regression-Analysis.git
   cd mileage-prediction

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt

3. **Run the Jupyter Notebook:**
   Open the Mileage_Prediction_Regression_Analysis.ipynb file in Jupyter Notebook or JupyterLab to see the complete analysis and results.

## Results 

### Linear Regression Model

Equation:

Mileage = 23.4 - 1.05 Displacement - 1.86 Horsepower - 4.10 Weight - 0.115 Acceleration + error

Model Accuracy:

1. Mean Absolute Error: value
2. Mean Absolute Percentage Error: value
3. R² Score: value

### Polynomial Regression Model

Model Accuracy:

1. Mean Absolute Error: value
2. Mean Absolute Percentage Error: value
3. R² Score: value

##Conclusion

The project demonstrates the use of linear and polynomial regression models to predict the fuel consumption of cars. The polynomial regression model shows an improvement in accuracy over the linear regression model.

##License

This project is licensed under the MIT License.

##Acknowledgments

1. The dataset was taken from the StatLib library which is maintained at Carnegie Mellon University.
2. The dataset was used in the 1983 American Statistical Association Exposition.
3. Special thanks to Ross Quinlan for the dataset modifications.
