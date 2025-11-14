House Price Prediction with Linear Regression
Overview

This project implements a Linear Regression model to predict house prices based on various features such as income, house age, number of rooms, number of bedrooms, and area population. It includes data cleaning, model training, evaluation, and comprehensive visualizations to analyze the dataset and model performance.

Project Structure
house_outputs/
│
├─ cleaned_house_data.csv        # Cleaned dataset after removing missing values
├─ metrics.txt                   # Model performance metrics (MSE, R2 Score)
├─ actual_vs_predicted.png       # Scatter plot of actual vs predicted prices
├─ residuals.png                 # Residual plot
├─ scatter_matrix.png            # Scatter matrix of all features + target
├─ coefficients.png              # Linear Regression coefficients
├─ feature_histograms.png        # Histograms of features and target
├─ correlation_heatmap.png       # Heatmap of feature correlations
├─ prediction_error_distribution.png  # Distribution of prediction errors
├─ pairplot.png                  # Pairplot with regression lines
├─ feature_importance.png        # Absolute coefficient feature importance
├─ boxplot_<feature>.png         # Boxplots of Price vs each feature

Dataset

The dataset is expected to be a CSV file named house.csv.

Features used:

Avg Area Income

Avg Area House Age

Avg Area Number of Rooms

Avg Area Number of Bedrooms

Area Population

Target:

Price

Installation

Clone this repository or download the files.

Make sure Python 3.x is installed.

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn

Usage

Place your house.csv dataset in the same folder as the script.

Run the script:

python house_price_regression.py


All outputs (plots, metrics, cleaned data) will be saved automatically in the house_outputs folder.

Outputs

Metrics: metrics.txt contains MSE and R2 score.

Plots: Various visualizations help analyze:

Actual vs predicted prices

Residuals

Feature distributions

Feature correlations

Prediction errors

Feature importance

Relationships between features and price

Cleaned Dataset: cleaned_house_data.csv has all missing values removed.

Notes

The script does not display plots during execution; all plots are saved automatically.

Boxplots group features into quintiles to visualize their effect on house prices.

This project provides a foundation for exploring advanced regression models and feature engineering.
