# Heart Disease Mortality Prediction 
# Analysis & Conclusions
Predicting Heart Disease Mortality with Machine Learning Techniques

Lorenzo Negri, July 2018

## Problem Overview

The analysis of data presented in this document concerns features of United States county-level area info, demographic and socioeconomic and the number of heart disease (per 100,000 individuals) which will be the prediction goal of the problem. 
The train dataset analysed consist in 3198 observations from a wide range of sources and made publicly available by the United States Department of Agriculture Economic Research Service (USDA ERS). Each observation contains 33 variables from different categories (2 for area information, 5 for economic indicators, 14 for demographics information and 11 health indicators) about the counties, plus a year identifier column that covers two particular years, denoted a, and b. 
The target variable: heart_disease_mortality_per_100k (a positive integer available in: train_labels.csv) will be joined later to the dataset in order to train a model and predict the target variable. For the analysis in this document, the label (target variable) was joined has the first step, but this will not be the first step of the train machine-learning model workflow because the label can create overfitting results when managing and predicting the missing data of the train dataset.   
Exploring data by summary statistics, and by creating visualizations, made possible to identify several potential relationships between features and heart disease mortality, leading to create (after analysing, cleaning and filtered the data) a machine learning regression model to predict an integer number of heart disease mortality per 100k giving some related variables. 

## Contents

[1. Problem Description, Overview and Interpretations] (https://github.com/LorenzoNegri/Heart-Disease-Mortality-Prediction/blob/master/01_ProblemDescription_Overview_Interpretations.pdf)
[2. Data Exploration] (https://github.com/LorenzoNegri/Heart-Disease-Mortality-Prediction/blob/master/02_Data_Exploration.pdf)
[3. Correlation Analysis] (https://github.com/LorenzoNegri/Heart-Disease-Mortality-Prediction/blob/master/03_Correlation_Analysis.pdf)
[4. Predictive analytics and Conclusions] (https://github.com/LorenzoNegri/Heart-Disease-Mortality-Prediction/blob/master/03_Correlation_Analysis.pdf)
