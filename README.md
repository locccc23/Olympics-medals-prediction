# Olympics Medals Prediction

This project focuses on understanding how a Linear Regression model works using an Olympic medals dataset. It also explores data preprocessing and how Mean Absolute Error (MAE) helps evaluate the difference between the model's predictions and the actual target values.

## Project Overview
This project uses multiple features to train a Linear Regression model and predict Olympic medal counts. It also analyzes the dataset and uses the chronological order of the data to split it into training and testing datasets.

## Technologies
*Python
*Numpy
*Pandas
*Skikit_learn
*Matplotlib

## Data Exploration & Preprocessing

The project includes:

- Loading the Olympic dataset with Pandas
- Exploring the dataset with `.head()` and `.describe()`
- Selecting columns relevant to medal prediction
- Checking correlations between numerical variables
- Visualizing medal distributions
- Checking for missing values
- Removing rows with missing values
- Splitting the data based on Olympic year

The data is split chronologically:

- **Training data:** Olympic years before 2012
- **Testing data:** Olympic years from 2012 onward

This allows the model to use earlier Olympic results to predict later results.

## 🤖 Machine Learning

This project uses **Linear Regression** to predict the number of medals.

### Features

The model uses historical/team information such as:

- `athletes`
- `prev_medals`

### Target

- `medals`

The model learns the relationship between the selected features and the number of medals won.

## Model Evaluation

The model is evaluated by comparing its predictions with the actual medal counts in the test dataset.

Evaluation includes:

- Mean Absolute Error (MAE)
- Prediction errors
- Comparison between predicted and actual medal counts

## What I Learned

Through this project, I practiced:

- Data exploration with Pandas
- Check and select the correlated features
- Handling missing data
- Creating training and testing datasets
- Training a Linear Regression model
- Evaluating regression models
- Visualizing data and model results

## Future Improvements

- Learn to implement feature engineering
- Testing different approaches to missing values
- Evaluating the model with additional metrics
- Improving prediction accuracy by working more on preprocessing
- Learn how to implement EDA to gain deep insight into the relationship
  between features and target.

## Project Structure

```text
olympics-medals-prediction/
│
├── olympics_medals_prediction.ipynb
├── teams.csv
└── README.md

