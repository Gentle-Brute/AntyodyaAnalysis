Agriculture Survey Data Analysis
This repository contains a Jupyter notebook for analyzing village-wise survey data related to agriculture. The analysis includes data cleaning, exploration, statistical modeling, and machine learning to predict the number of households engaged majorly in farm activities. The dataset used is from the Mission Antyodaya 2020 survey.

Dataset
The dataset village_wise_survey_data_mission_antyodaya_2020.csv contains information about various aspects of villages including farming activities, irrigation sources, and infrastructure availability. The dataset is cleaned and processed to prepare it for analysis.

Analysis Steps
Data Cleaning: The dataset is cleaned by removing unnecessary columns, handling missing values, and converting categorical variables into a suitable format for analysis.
Exploratory Data Analysis: Various statistical analyses are performed to understand the distribution of variables and their relationships. This includes calculating descriptive statistics, identifying significant variables, and visualizing data using plots.
Statistical Modeling: Ordinary Least Squares (OLS) regression is used to model the relationship between the number of households engaged in farm activities and other variables in the dataset. Anova is used to select significant variables for the model.
Machine Learning: Several machine learning algorithms including Linear Regression, Ridge Regression, Lasso Regression, ElasticNet, and Random Forest Regression are applied to predict the number of households engaged in farm activities. The models are evaluated using Mean Squared Error (MSE) and R-squared scores.
Files
agriculture_survey_analysis.ipynb: Jupyter notebook containing the analysis code.
Agriculture.csv: Processed dataset after cleaning and feature engineering.
LinearRegression.joblib, Ridge.joblib, Lasso.joblib, ElasticNet.joblib, RandomForestRegressor.joblib: Saved models for each algorithm.
Requirements
Python 3.x
Libraries: numpy, pandas, seaborn, matplotlib, statsmodels, scikit-learn, tqdm, joblib, re.
Usage
Clone the repository:
bash
Copy code
git clone https://github.com/your_username/agriculture-survey-analysis.git
Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook:
bash
Copy code
jupyter notebook agriculture_survey_analysis.ipynb
Follow the instructions in the notebook to execute the analysis and explore the results.
Contributors
Your Name
