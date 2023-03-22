# Heart-Disease-Prediction

### Data
●	Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of 5CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs and this dataset contains 11 features that can be used to predict a possible heart disease.
●	People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

There are 14 columns in the dataset, where the patient_id column is a unique and random identifier. The remaining 13 features are described in the section below.

### Conclusion
Men seem to be more susceptible to heart disease than women. Increasing age, systolic blood pressure also show increasing chances of heart disease.

The Logistic model predicted with an accuracy of 0.76 whereas SVM model predicted with an accuracy score of 0.84. The model is more specific than sensitive.

The general model can be improved with more data.

Case 1 = if the person has a heart disease and the model predicted it as false(FN)

Case 2 = if the person doesnot have a heart disease and the model predicted it as True(FP)

In case 1 it would be more dangerous for a person to not receive the treatment even after having a disease hence we need to select a model with high recall score

 ### Result table


                          precision     recall  f1-score 
            
     Logistic                0.88       0.85      0.87 
 
     SVM                     1.00       0.75      0.85
     
     KNN                     1.00       0.70      0.82
     
     Decision                0.83       0.50      0.62
     Tree
     (Hyperparameter)        0.85       0.55      0.67
     
     Random                  0.93       0.65      0.76
     Forest 
     (Hyperparameter)        0.1        0.70      0.82
 
 ### Result :
     ##### As we can see case 1 is more problematic which is False Negative, so in these scenario recall score  should be high. Logistic is having  high recall score than any other model. We can say Logistic regression is a better model for further predictions.
