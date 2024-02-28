# Credit-risk-analysis

Starting form a Kagle data set. Aiming to assess the expected Loss of a bank debtors. The process involved: the preprocessing of the data, building a Probability of Default model, validated a Probability of Default model, creating scorecards, monitoring the population, creating Loss Given Default and Exposure at Default models

Flow and files:

Raw Data: loan_data_2007_2014.csv from: https://www.kaggle.com/datasets/devanshi23/loan-data-2007-2014

Part 1: Preprocessing: clean the data, check for missing values, determine the dependent variable, applying coarse classing using WoE/IV for creating dummy variables
Code: Preparation.ipynb 
Data Stored in: 
                - loan_data_inputs_train.csv
                - loan_data_inputs_test.csv
                - loan_data_targets_train.csv
                - loan_data_targets_test.csv
                - ref_categorie.csv
                - loan_data_2007_2014_for_LGD_EAD.csv

                ****************** TO DO: dummy in all files FACk
