# Agriculture Survey Data Analysis

## Overview
This repository contains a Jupyter notebook for analyzing village-wise survey data related to agriculture. The analysis focuses on understanding various factors influencing the number of households engaged majorly in farm activities.

## Dataset
The dataset used in this analysis is the `village_wise_survey_data_mission_antyodaya_2020.csv` file, which contains information about different villages, including their agricultural practices, infrastructure, and resources.

## Analysis Steps
1. **Data Cleaning:** The dataset is cleaned to handle missing values and standardize column names.
2. **Exploratory Data Analysis:** Statistical tests such as ANOVA are performed to identify significant factors influencing household engagement in farming.
3. **Feature Engineering:** New features are created, and categorical variables are encoded for modeling.
4. **Modeling:** Several regression models (Linear, Ridge, Lasso, ElasticNet, RandomForest) are trained to predict the number of households engaged in farm activities.
5. **Model Evaluation:** The models are evaluated based on their accuracy scores and mean squared errors.

## File Description
- `Agriculture.ipynb`: Jupyter notebook containing the entire analysis pipeline.
- `Agriculture.csv`: Cleaned dataset used for analysis. (Main data - https://drive.google.com/drive/folders/1UcO03qqdl3QTRZKtJreEUpKIh0Ab2j8L)
- `LinearRegression.joblib`, `Ridge.joblib`, `Lasso.joblib`, `ElasticNet.joblib`, `RandomForestRegressor.joblib`: Saved model files.

## Instructions
1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/Gentle-Brute/AntyodyaAnalysis
   ```
2. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to reproduce the analysis or use the provided models for predictions.

## Contributors
- Garv Bhatia and Husain Chhil
- garvbhatia04@gmail.com, hychhil@gmail.com
