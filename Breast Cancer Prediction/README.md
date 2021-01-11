Breast Cancer Analysis and Prediction Projects

![Banner1](https://user-images.githubusercontent.com/76062093/103670710-f0022980-4f9f-11eb-94be-e27c7f7bc8aa.png)


Project Overview

Create a model to Predict whether the cancer is benign or malignant

Attribute Information:

1) ID number

2) Diagnosis (M = malignant, B = benign)

3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

In this Project I have Used Machine Learning algorithm:

1) LogisticRegression

2) Decision Tree

3) K-Nearst Neighbors Classifier

4) Support Vector Machine (SVM)

5) Stock Hosting Gradient Boosting Classifier

6) Naive Bayes Classifier

    > GaussionNB
    
    > MultinomialNB
    
    > BernoulliNB
  
7) Random Forest Classifier

8) Bagging Classifier

9) AdaBoost Classifier

10) XGBoost Classifier

11) Gradient Boosting Classifier

Exploring the data set with Visulization:

![digonastic](https://user-images.githubusercontent.com/58104706/93659052-eee3d580-fa5e-11ea-9bb1-f56c00eef6f4.png)


Above chart repersent the Bening and Mailngnant The Benign is more than to the Mailngnant values in this data set.


Correlation Matrix Visulization With all the Features:

![correlation matrix](https://user-images.githubusercontent.com/58104706/93659238-c8269e80-fa60-11ea-9225-57e0a49a41d2.png)


Boxplot all models using cross validation method.


![boxplot](https://user-images.githubusercontent.com/58104706/93659413-7848d700-fa62-11ea-93d8-6759236dc80e.png)






