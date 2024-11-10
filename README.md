
# Insurance Claim Prediction Using Logistic Regression

## Project Overview

This project aims to build a predictive model using Logistic Regression to estimate the probability of customers making insurance claims. By analyzing historical data, the model helps in identifying key factors that influence the likelihood of a claim, which can be useful for risk assessment and decision-making in the insurance industry.

## Project Structure

The repository contains the following files:
- `Insurance_Logistics_Regression.ipynb`: Jupyter Notebook with data analysis and Logistic Regression model implementation.
- `README.md`: Detailed explanation of the project and findings.

## Key Objectives

1. **Data Exploration**: Analyze the dataset to identify patterns and understand key metrics.
2. **Data Preprocessing**: Clean and prepare the data for modeling, including handling missing values and encoding categorical variables.
3. **Model Development**: Build and evaluate a Logistic Regression model to predict insurance claims.
4. **Insights & Recommendations**: Interpret model coefficients and provide actionable insights based on the findings.

## Tools & Technologies

- **Python**: Programming language for data analysis and model building.
- **Pandas & NumPy**: Libraries for data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization tools.
- **Scikit-learn**: Machine learning library for Logistic Regression and model evaluation.

## Dataset

The dataset includes information on customer demographics, policy details, and previous claim history. Key features include:
- `Age`: Age of the customer.
- `Policy Type`: Type of insurance policy held by the customer.
- `Claim History`: Previous claim records.
- `Annual Premium`: Amount paid annually for the insurance policy.
- `Target Variable`: Indicator of whether a claim was made (0 = No, 1 = Yes).

## Methodology

1. **Data Preprocessing**:
   - Handle missing values and encode categorical variables.
   - Normalize numerical features for better model performance.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize the distribution of features and relationships with the target variable.
   - Check for multicollinearity among features.

3. **Model Development**:
   - Split the data into training and testing sets.
   - Train a Logistic Regression model using the training data.
   - Evaluate the model's performance using metrics like accuracy, precision, recall, and AUC-ROC score.

4. **Model Evaluation**:
   - The model achieved good accuracy in predicting insurance claims.
   - AUC-ROC score was used to assess the classifier's ability to distinguish between claim and non-claim cases.

## Results & Insights

- Customers with a higher number of previous claims have a greater likelihood of making a claim.
- Certain policy types and higher annual premiums were found to be significant predictors of claim probability.
- The model’s predictions can be used by insurance companies to assess risk and make informed policy decisions.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/portfolio_projects.git
   ```
2. Navigate to the project directory:
   ```bash
   cd portfolio_projects
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Insurance_Logistics_Regression.ipynb
   ```

## Conclusion

The Logistic Regression model provides valuable predictions on the likelihood of insurance claims, which can help in risk management and strategic decision-making for insurers. This project highlights the use of a straightforward yet effective machine learning model for classification tasks in the insurance domain.

