midterm_project

This is the submission for the West Coast group with Carly & David. We created a notebook for each EDA task and have multiple notebooks for the modelling questions. These are all within the python_code folder. You will see a folder for visualizations that we used during the presentation. This isn't really relevant.

**********************Important*************************
Test_Flight_clean.ipynb is the notebook required to exactly replicate the submission_cleaned.csv that is our final submission. This notebook reads in the flights_test table, as well as 4 small .csv's that act as our "keys" to engineer our weather, and historical aggregate features.

model_5.ipynb contains the model that performed the best for the regression submission.model_5 contains the winning model for the regression submission. We used XGB after doing PCA and using 15 principal components.


sumission_cleaned.csv is located in this google drive folder:
https://drive.google.com/drive/folders/1ChYgg16rPNTfED_Foqz-NvwzYJpIbeQs?usp=sharing
********************************************************

The EDA notebooks are labelled Tasks 1-10.

The modelling Notebooks are labelled as follows:

1. BINARY_CLASS.ipynb: this notebook contains the code to perform the data cleaning, modelling and evaluation for the binary classification problem of trying to predict classifications. This model achieved perfect results but I'm very interested in feedback because it seems too good to be true.

2. Feature_Eng_Fennell.ipynb: this notebook contains code to engineer the weather features. This is where you will find the code that exports the file wkey.csv (this is used to generate features with the test data set)

3. data_clean_explore.ipynb & flights_data_cleaning.ipynb: these two notebooks are doing some very initial data exploration and cleaning. 

4. model_1-model_5 are various regression models attempted to fit the data. model_5 contains the winning model for the regression submission. We used XGB after doing PCA and using 15 principal components. model_4 contains some code for hyperparameter tuning that was done.

5. model_multiclass_classification.ipynb: this notebook contains code to perform the multiclassification problem.

6. modeling.ipynb is the first linear regression model we built and is not important.

7. model_multiclass_classification.ipynb is the notebook used to perform the multiclass modelling. Tried 4 different models for this problem (Naive Bayes, Bagging, XGB, ADABOOST Naive). The Bagging Ensemble performed the best in terms of accuracy, precision and recall.


Also within the google drive folder are the keys required to regenerate that file within Test_Flight_clean.ipynb.

We would have added it to github but it was 300 MB and the limit on git is 100 MB

ENJOY :))))))))) 

Looking forward to feedback.








