#### Challenge 17: Module 17

# Overview of Project

## Purpose of Credit Risk Analysis

During module 17, the use of different Machine Learning models were used to analyze loans. In the challenge, the analyzed topic is “credit risk”, being an unbalanced classification sample. One of the most important parts of the challenge is to use imbalanced-learn and scikit-learn libraries to resampling the model and evaluate the results. The algorithms used to oversample are RandomOverSampler and SMOTE, and the one for undersample is ClusterCentroids. Also the SMOTEENN algorithm was used for a combinatorial approach of over- and undersampling. At the end of the challenge, two Machine Learning models that reduce bias were compared for credit risk.


# Results

Classification reports made with each Machine Learning model are located in the next section. Six models were used, having six complete tables for each, including their balanced accuracy scores and the precision.

* Naive Random Oversampling

The balanced accuracy score is 0.6573, and the precision for high risk is 0.01 and 1.00 for low risk. 

###### Image 1. Imbalanced classification report.

![Image 1. Imbalanced classification report.](Resources/NROversampling.PNG)


* SMOTE Oversampling

The result for the SMOTE in accuracy is 0.6624 and the results for precision were similar to the ones for Naive Random Oversampling.

###### Image 2. Imbalanced classification report.

![Image 2. Imbalanced classification report.](Resources/SMOTE.PNG)


* Undersampling

For Undersampling, the balanced accuracy score is lower than the previous scores, being 0.5443 the value and the results for precision are also similar to the others.

###### Image 3. Imbalanced classification report.

![Image 3. Imbalanced classification report.](Resources/Undersampling.PNG)


* Combination (Over and Under) Sampling

The result for Combination Sampling in balanced accuracy score is 0.6447, the score is near other scores mentioned. The precision in this case is also 0.01 for high risk and 1.00 for low risk. 

###### Image 4. Imbalanced classification report.

![Image 4. Imbalanced classification report.](Resources/Combination.PNG)


* Balanced Random Forest Classifier

The next two models were created to analyze the bias. In this case, the balanced accuracy score is 0.7885, a higher value than the others. The precision in the model changed, being 0.03 for high risk and 1.00 for low risk. 

###### Image 5. Imbalanced classification report.

![Image 5. Imbalanced classification report.](Resources/brf.PNG)


* Easy Ensemble AdaBoost Classifier

The other model to analyze bias, obtained a balanced accuracy score of 0.9316, the higher score of all the model results. The precision for high risk is 0.09 and for low risk 1.00. 

###### Image 6. Imbalanced classification report.

![Image 6. Imbalanced classification report.](Resources/eeac.PNG)


# Summary
