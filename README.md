# Overview

In this project we took credit card data from LendingClub's first quarter to create an algorithm to determin the risks of loans. We did this by splitting the data and oversampling and undersampling the data. We then compare the two modles to see if they can accurately predict credit risk. With this information we can help our client make better decisions on their lending.

# Results

* Random Oversampling
![](https://github.com/RonHolcomb/Credit_Risk_Analysis/blob/main/Screenshot%20(35).png)
In this sample we can see that we have a 63% accuracy score. A 100% precision low risk with a 1% precision high risk. The recall is pretty even but it is favored to be low. 

* SMOTE Oversampling
![](https://github.com/RonHolcomb/Credit_Risk_Analysis/blob/main/Screenshot%20(36).png)
In this sample we can see that the data stayed about the same. We still have a 63% accuracy score. A 100% precision low risk with a 1% precision high risk. This time the recall is favored to be a bit higher in risk.

* Undersampling
![](https://github.com/RonHolcomb/Credit_Risk_Analysis/blob/main/Screenshot%20(37).png)
The undersampling is much different with only a 51% accuracy score. Still a 100% precision low risk with a 1% precision high risk. The recall is way higher in risk this time around

* Combination Over & Undersampling
![](https://github.com/RonHolcomb/Credit_Risk_Analysis/blob/main/Screenshot%20(38).png)
In the combination sampling we have a 62% accuracy score. The same 100% precision low risk with a 1% precision high risk, and the recall is still favors a higher risk by 10%

* Balanced Random Forest Classifier
![](https://github.com/RonHolcomb/Credit_Risk_Analysis/blob/main/Screenshot%20(39).png)
Here we see a very high accuracy score of almost 80%. The precision low risk remains at 100% while the high has gone up to 4%. The recall shows a low risk of 91% but a high of 69%

* Easy Ensemble AdaBoost Classifier
![](https://github.com/RonHolcomb/Credit_Risk_Analysis/blob/main/Screenshot%20(40).png)
