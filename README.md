# House-Price-Prediction-using-Random-Forest-Regressor-and-Grid-Search

## Overview
This project aims to predict median house prices in a given region based on various features such as the number of rooms, bedrooms, population, and geographical coordinates. The dataset used for this project is the California Housing dataset from the StatLib repository.

## Features
- Exploratory Data Analysis (EDA) on the housing dataset
- Data preprocessing techniques (handling missing values, feature engineering, etc.)
- Implementation of Linear Regression and Random Forest Regression models
- Hyperparameter tuning using GridSearchCV
- Model evaluation and feature importance analysis

## Usage
1. Clone the repository using
   ```
    git clone https://github.com/sushantkothari/House-Price-Prediction-using-Random-Forest-Regressor-and-Grid-Search.git
   ```
3. Install the required dependencies
4. Run the jupyter notebook

## Data
The California Housing dataset is used in this project. It consists of the following features:

- `longitude`: A measure of how far west a house is; a higher value is farther west.
- `latitude`: A measure of how far north a house is; a higher value is farther north.
- `housing_median_age`: Median age of the house in the block.
- `total_rooms`: Total number of rooms in the block.
- `total_bedrooms`: Total number of bedrooms in the block.
- `population`: Number of people residing in the block.
- `households`: Number of households in the block.
- `median_income`: Median income for households in the block.
- `median_house_value`: Median house value for households in the block.
- `ocean_proximity`: Proximity to the nearest ocean.

## Key Steps in Data Preprocessing
1. Handling missing values by dropping rows with NaN values.
2. Splitting the dataset into training and testing sets.
3. Applying log transformation to features with skewed distributions.
4. One-hot encoding of categorical features.
5. Creating new features (e.g., bedroom_ratio, household_rooms) using existing features.
6. Scaling numerical features using StandardScaler.

## Machine Learning Models
1. Linear Regression
2. Random Forest Regression

## Model Evaluation and Feature Importance
- Model evaluation is performed using the coefficient of determination (R-squared) metric.
- Feature importance is analyzed for the Random Forest Regression model.

## Results
The Random Forest Regression model outperformed the Linear Regression model, achieving a higher R-squared score on the test set.

## Conclusion and Future Work
This project demonstrates the application of machine learning techniques to predict median house prices based on various features. The Random Forest Regression model showed better performance compared to Linear Regression.

Future directions for this work include:
- Exploring other regression models (e.g., gradient boosting, neural networks)
- Incorporating additional relevant features
- Investigating advanced feature engineering techniques
- Deploying the model as a web application or API

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an issue for any improvements or bug fixes.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- The California Housing dataset is provided by the StatLib repository.
- This project was inspired by various machine learning tutorials and resources.

## Contact
For any questions or inquiries, please contact me at sk619kothari@gmail.com.
