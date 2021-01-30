Final year project for IFT 6758 - Data Science
Team: Social Dilemma
Members: Vijaya Lakshmi kuruba   Marthy Stivaliz Garcia Alvarado   Lissethy Cevallos   Karla Felix Navarro


In this challenge, we use different Data cleaning strategies, Imputation techniques and Machine Learning models to predict the Number of Likes based on Social Media Profile of different users. The code for the best model is uploaded to this repo.


Files for Best submission. This folder contains the following files:

-Best_submission.csv corresponds to the prediction generated.
-Social_Dilemma_Best_Score_Submission.ipynb. Python notebook to generate file
-train.csv. CSV file containing the training dataset
-test.csv. CSV file containing the test dataset
-Procedure to execute python notebook:

Upload training and testing dataset into colab. Dataset should be called "train.csv" and "test.csv", respectively.
Run colab until section Submission File. Run cell Submission file. The latter will generated the predictions on the test dataset. 
Notes: 
1.All the parameter tuning cells have been commented. 
2.EDA has commented. It is not required for submission generation.
3.Cells after submission file are use for evaluation purposes.

Submission.csv will be automatically generated and saved.
In detail, the following steps are part of the colab file:

-Study data by exploratory data analysis and do Feature engineering.

-preprocessing the data

-Test train split data

-Fit the model and experiment of different models

-For the best ensembler fit the model and generate submission file
