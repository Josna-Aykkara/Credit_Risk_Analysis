# Credit_Risk_Analysis

## Overview of the analysis

The purpose of the analysis is to develop a model to predict credit risk associated with the loan using the dataset provided. We are using the machine learning models to reduce any bias associated with the analysis using the Balanced Random Forest Classifier and Easy Ensemble Classifier model algorithms to predict the credit risk. The Imbalanced learn and Scikit learn libraries are used for this analysis. 

## Results 

1.	**Naive Random Oversampling**

•	*Balanced accuracy score: 66.14%*
 ![This is an image]( https://github.com/Josna-Aykkara/Credit_Risk_Analysis/blob/main/Images/oversample.JPG)

2.	**SMOTE Oversampling**

•	*Balanced accuracy score: 64.26%*
 ![This is an image]( https://github.com/Josna-Aykkara/Credit_Risk_Analysis/blob/main/Images/SMOTE.JPG)

3.	**Under Sampling**

•	*Balanced accuracy score: 53.11%*

 ![This is an image]( https://github.com/Josna-Aykkara/Credit_Risk_Analysis/blob/main/Images/under.JPG )
 
4.	**Combination (Over & Under) Sampling**

•	*Balanced accuracy score: 65.85%*
	![This is an image]( https://github.com/Josna-Aykkara/Credit_Risk_Analysis/blob/main/Images/combination.JPG )
  
5.	**Balanced Random Forest Classifier**

•	*Balanced accuracy score: 78.85%*
 ![This is an image]( https://github.com/Josna-Aykkara/Credit_Risk_Analysis/blob/main/Images/bal%20forest%20c.JPG )
 
6.	**Easy Ensemble AdaBoost Classifier**

•	*Balanced accuracy score: 93.17%*
	![This is an image]( https://github.com/Josna-Aykkara/Credit_Risk_Analysis/blob/main/Images/easy%20ensemble%20Ada.JPG )
  
## Summary

Based on the different models used for the analysis, the highest accuracy rate of 93% was achieved by using the Easy Ensemble AdaBoost Classifier. The precision is towards the higher side compared to all the models build.

The recommendation is to use the Easy Ensemble AdaBoost Classifier model as it has a higher accuracy rate of above 93%. The precision rate for high-risk is 9% and recall rate is 92% for the model. It highlights that there is better prospect for high risk of loans due to the higher recall rate and should take additional care while lending money. 
