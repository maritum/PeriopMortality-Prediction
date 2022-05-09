# PeriopMortality-Prediction

This repo is for code used in the Preoperative Surgical Risk Prediction project. For details, please see our paper:

[Integration of Feature Vectors from Raw Laboratory, Medication and Procedure Names Improves the Precision and Recall of Models to Predict Postoperative Mortality and Acute Kidney Injury, 2022
Ira S. Hofer, Marina Kupina, Lori Laddaran, Eran Halperin](https://www.researchgate.net/publication/357614628_Integration_of_Feature_Vectors_from_Raw_Laboratory_Medication_and_Procedure_Names_Improves_the_Precision_and_Recall_of_Models_to_Predict_Postoperative_Mortality_and_Acute_Kidney_Injury)



# Training/testing the model

If you do not have Anaconda installed, first install it as described [here](https://www.anaconda.com/distribution/). Once you have Anaconda installed, create the Anaconda environment using the command

`conda env create -f environment.yml`

This should install the packages needed to run code for training/testing the model.








#### PeriopMortality_prediction.ipynb

This notebook is the primary notebook for filtering the data, training the models, and measuring performance.


#### Visualization.ipynb

Once the predictions have been generated for the various models, this notebook plots the ROC curve and the PR curves for each model over all feature sets.

#### FeatureSelection.ipynb

This notebook is for selection features using Boruta.
