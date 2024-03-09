# Financial-Analysis-for-Lululemon-Stock
This project focuses on conducting a comprehensive financial analysis for Lululemon stock. The Python coding was executed using Google Colab, leveraging various machine learning and statistical techniques.

Project Objectives
The primary objectives of this project include:

1. Analyzing Lululemon stock and its competitors.
2. Constructing a feature database using various factors and features.
3. Visualizing feature importance and selection processes using regression and decision tree-based approaches.
4. Training and evaluating 3-6 models to predict stock prices or returns.
5. Including a benchmark study utilizing GARCH or Kalman Filter models.

Project Requirements : 
1. Summary Statistics and Kernel Density Plot: Report summary statistics of the selected training period and plot the kernel density of the stock and its competitors.
2. Feature Database Construction: Use various features and factors from sources like FRED, Fama-French website, ADS, AR, CAPM, momentum factors, volume, price/return lags, etc., to construct a feature database. The target variable Y can be either price or return, with daily or monthly frequency.
3. Feature Importance and Selection Visualization: Visualize the feature importance and selection process using regression-based approaches (Ridge regression, LASSO, Elastic Net, or LARS) versus decision tree-based approaches (random forest, XGBoost).
4. Model Training and Evaluation: Propose and train 3-6 models using the prepared features. Compare model performance using RMSE between the fitted Y and actual Y in the testing period.
5. Benchmark Study: Include one benchmark study using GARCH or Kalman Filter models.
6. Trading Rules and Signals: Compose trading rules using buy-and-hold, long-short, or day trade strategies. Generate trading signals using the above 3-6 models. Compare their PnL.

Project Structure : 

Notebooks: Contains Python notebooks used for data preprocessing, feature engineering, model training, and analysis.

Data: Includes datasets used for Lululemon stock and its competitors.

Presentations: Contains the final project presentation files addressing the requirements mentioned above.

README.md: This file provides an overview of the project and its components.
