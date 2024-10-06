# Ames-Housing-Data-Analysis-and-Model-Prediction_DEPI-
Ames Housing Price Prediction using Decision Tree Regressor

## overview
this is data analysis project using the Ames Housing dataset, which involved several key steps to predict house prices through data preprocessing, exploratory analysis, and model building with a Decision Tree Regressor.

## Project Highlights:
- Data Exploration:
  - Analyzed the dataset containing 2,931 rows and 82 columns to understand its structure.
  - Conducted descriptive statistics on both numerical and categorical variables to gain insights into the data distribution.

## Data Preprocessing:
  - Handling Missing Values: Dropped columns with over 20% missing values and filled missing values in Lot Frontage with the mean.
  - Removing Duplicates: Cleaned the dataset by removing duplicate entries based on the unique PID column.
  - Feature Selection: Computed the correlation of numeric features with the target variable (SalePrice) and eliminated uncorrelated features to focus on relevant 
     data.
    
## Categorical Encoding:
  - Employed One-Hot Encoding to convert categorical features into a format suitable for modeling, ensuring the model could effectively learn from the data.

## Model Training and Evaluation:
  - Split the data into training and testing sets, and implemented a Decision Tree Regressor.
  - Used GridSearchCV for hyperparameter tuning, optimizing parameters such as max_depth and min_samples_leaf.
  - Achieved a promising R² score on both training and testing datasets, validating the effectiveness of the model.
 
## Prediction Functionality:
  - Developed a function to preprocess new data and make predictions, ensuring that the model can be applied to real-world scenarios.
