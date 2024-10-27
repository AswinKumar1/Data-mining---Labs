# Business Problem

- In this task, we were askeed to build supervised machine learning with Logistic Regression (LR), Naïve Bayes (NB), Support Vector Machine (SVM), and Decision tree (DT), Random Forest (RF) classifiers, as compared with simple/baseline methods. The data for this exercise comes from the wine industry. Each record represents a sample of a specific wine product, the input attributes include its organoleptic characteristics, and the output denotes the quality class of each wine: {high, low}. The labels have been assigned by human wine-tasting experts, and we can treat that information as “ground truth” in this exercise.  Our job is to build the best model to predict wine quality from its characteristics so that the winery can replace the costly services of professional sommeliers with the automated alternative to enable quick and effective quality tracking of their wines at production facilities. They need to know whether such change is feasible and what extent inaccuracies may be involved in using your tool.

## Dataset used for this exercise: red_wine.csv and white_wine.csv. 

# Tasks:
- Read  red-wine.csv into Python as a data frame, use a pandas profiling toolto create an HTML file. 
- Fit a model using each of the following methods and report the performance metrics of 10-fold cross-validation using red-wine.csv as the training set and report the AUC and Accuracy for all the models including the base model. 
- Plot the ROC curve of the Random Forest classifier from the Python package. 
- Using the best performing model for red_wine dataset, construct the same model for white_wine.csv dataset and report it's AUC and Accuracy. 
- If all the models have comparable performance, comment the insights on preferred model of choice which can be used by experts to gain some insights into the model. 

