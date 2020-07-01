# Predicting-Earnings-Manipulation-by-Indian-Firms-using-Machine-Learning-Algorithms

This is an analysis of a case study on predicting earnings manipulation using data purchased from [Harvard Business Review](https://store.hbr.org/product/predicting-earnings-manipulation-by-indian-firms-using-machine-learning-algorithms/IMB577). 

The eight financial indices of the Beneish Model have been used to predict earning manipulators by Indian firms using Machine Learning algorithms. The models have been compared with the Beneish model seeking a model more suitable for an unbalanced data having more number of non-manipulators than manipulators. The unbalanced data has been handled using undersampling techniques for better performance, precision and accuracy.

### Machine Learning techniques used in performance analysis:
* Decision Tree (Classification and Regression Tree - CART)
* Logistic Regression
* Random Forest
* AdaBoost 

### FINAL ANALYSIS:
                   
##Logistic Regression Model :
* Accuracy : 86.67%
* Precision : 95.24%
* Equation: y = -14.9907 + 4.2540DSRI + 5.7864SGI + 0.9798AQI + 14.0498ACCR + 1.2567GMI
* Area under curve:  0.863
* Key predictors: ACCR > SGI > DSRI > GMI > AQI 


Decision Tree Model (CART) : 
* Accuracy : 82%
* Precision : 80%
* Area under curve:  0.721
* Key predictors: ACCR > DSRI > DEPI
                 
Random Forest :
* Accuracy : 75%
* Precision : 89.74%
* Area under curve : 0.825
* Key predictors: SGI > ACCR > LEVI > SGAI > DSRI > GMI > DEPI > AQI


ADA boost :
* Accuracy : 63.33%
* Precision : 83.33%
* Key predictors: SGAI > ACCR > DEPI > SGI
          
## CONCLUSION :  
* Out of all the models, Logistic regression model is the best model with highest accuracy, precision and AUC(ROC Curve)
* For predicting earning manipulators, the following varaibles can be used as predictors : ACCR, SGI, DSRI, DEPI
