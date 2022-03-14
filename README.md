# machine_learning_homework
The homework is composed by 2 notebooks.
## Notebook 1 (credit_risk_resampling)
 
This notebook was giving us a dataframe with some columns that needed to be encoded in order to be working with the models so i used the get_dummies solution to formulate the encoding and then executed the following steps : 
*Splitted the data into Training(X) and Testing(y).
*Checked the data with .describe and .value_counts.
*Created the train and test split data utilizing train_test_splot from sklearn.
*Scaled and trained the data with StandardScaler form sklearn.
*Applied Simple Logistic Regression Model then calculated balanced accuracy score, displayed confusion matrix and imbalanced classification report.
### Part 2 Oversampling
In this section we compared two oversampling algorithms (Random Over Sampler and SMOTE).
*Created the variable ros to assign the randomoversampler function.
*Fitted the data with .fit_resample and .fit
*Utilized Counter from collections library to count the target classes.
*Repeated the same steps of the previous model to display the results.
*Utilized similar process for SMOTE.
### Part 3 Undersampling
In this section we utilzed the Cluster Centroids algorithm (steps are almost identical).
### Part 4 Combination Sampling
In this section we tested a combination of over-under-sampling algorithm utilizing Smoteenn.
### Final Questions

## Notebook 2 (credit_risk_resampling)
In this notebook we repeated the first steps as before (data cleaning and split) and then got to the Balanced Random Forest classifier part.
### Balanced Random Forest
*Resampled the training data with the BalancedRandomForestClassifier.
*Generated a prediction (.predict) utilizing X_test_scaled as target.
*Calculated balanced accuracy score, displayed confusion Matrix and printed imbalanced classification report.
*Listed the features by importance in descending order.
### Easy Ensemble 
*processed similar process for training utilizing EasyEnsembleClassifier and used X_test as predict target.
### Final Questions
