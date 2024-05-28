# Life Expectancy Prediction Project

This repository contains the code and resources for the Life Expectancy Prediction Project, which aims to predict life expectancy based on various health, economic, and social factors. This project is part of a data science portfolio and demonstrates end-to-end model development, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and interpretation.

## Project Overview

Life expectancy is a critical measure of a country's health and development. This project uses a dataset containing various indicators to predict life expectancy. The main steps of the project include:

1. Data Preprocessing
2. Exploratory Data Analysis (EDA)
3. Model Selection and Training
4. Hyperparameter Tuning
5. Model Interpretation
6. Model Saving

## Dataset

The dataset used in this project is 'Life Expectancy Data.csv', which contains the following columns:
- Country
- Year
- Status
- Life expectancy
- Adult Mortality
- Infant deaths
- Alcohol
- Percentage expenditure
- Hepatitis B
- Measles
- BMI
- Under-five deaths
- Polio
- Total expenditure
- Diphtheria
- HIV/AIDS
- GDP
- Population
- Thinness 1-19 years
- Thinness 5-9 years
- Income composition of resources
- Schooling

## Project Structure

- `data/`: Contains the dataset file 'Life Expectancy Data.csv'.
- `notebooks/`: Jupyter notebooks for data analysis and model development.
- `models/`: Directory to save trained models.
- `README.md`: Project overview.
## Key Components

### Data Preprocessing

Code to handle missing values, encode categorical variables, and scale numerical features.

### Exploratory Data Analysis (EDA)

Code to visualize the distribution of variables, correlation matrix, pair plots, and other insights.

### Model Selection and Training

Code to train and evaluate multiple models (Linear Regression, Random Forest, Gradient Boosting) and select the best model based on performance metrics.

### Hyperparameter Tuning

Code to perform hyperparameter tuning for the best model using GridSearchCV.

### Model Interpretation

Code to interpret the model using feature importance and permutation importance.

### Model Saving

Code to save the trained model using joblib for future use.

## Usage

To run the project, follow these steps:
1. Preprocess the data.
2. Perform EDA to understand the data better.
3. Train multiple models and evaluate their performance.
4. Tune hyperparameters for the best model.
5. Interpret the model to understand feature importance.
6. Save the final model for future predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to open an issue or contact me at [subhro2002@gmail.com].
