# ML-MAJOR-AUG-ML081B2
# Coronary-Heart-Disease-Prediction
This is the Jupyter Notebook and the Dataset for the mentioned Classification Predictive Modeling

# About the dataset:
The "Framingham" dataset is publically available on the Kaggle website, and it is from an ongoing cardiovascular study on residents of the town of Framingham, Massachusetts. The classification goal is to predict whether the patient has 10-year risk of future coronary heart disease (CHD).The dataset provides the patients’ information. It includes over 4,240 records and 15 attributes.

# Objective: To build a classification model that predicts Ten Year Coronary Heart Disease in a subject.
# I have performed the following steps:
- Read the file and displayed its columns.
- Handled missing values, Outliers and Duplicate Data.
- Calculated basic statistics of the data (count, mean, std, etc), did exploratory analysis and described my observations.
- Resampled the imbalanced dataset by oversampling the positive cases.
- Selected columns that will probably be important to predict heart disease.
- Created training and testing sets (using 60% of the data for the training and reminder for testing) and scaled the data using MinMaxScaler.
- Built 5 different machine learning models to predict TenYearCHD: 
                                      * Logistic Regression - 67.56% Accuracy 
- kNN Classification - 89.98% Accuracy 
- Random Forest Classification - 90.39% Accuracy 
- Decision Tree Classification - 86.66% Accuracy 
- Gradient Boosting Classification - 71.46% Accuracy
- Hyperparameter tuned the RandomForestClassification - 95.77% and GradientBoostingClassification - 95.21%.
- Evaluated each model (f1 score, Accuracy, Precision ,Recall and Confusion Matrix) and plotted a graph for the false positive rate and true positive rate for each model.
- Ensembled the four best models using Stacking technique to further increase the accuracy of the model and achieved an accuracy score of 96.17%
- Concluded that Ensembling all the four most important models, with Random Forest Classification leading the way, has resulted in a very high accuracy score.
