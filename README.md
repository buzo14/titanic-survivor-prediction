# titanic-survivor-prediction

## Introduction 
These datasets need no introduction as data enthusiasts have widely used them to practice their data skills. This project entailed predicting the survival of passengers onboard the Titanic ship.
Our datasets (training & testing) are seen to be comprised of both numerical and categorical variables and some missing data.

![](titanic1.PNG)

## Preprocessing
On observation, we see some columns that will be useless to our model - Name, Ticket, and Pclass.
We drop them and proceed to preprocess our datasets. Since we have some missing data, using SimpleImputer and OneHotEncoder SKlearn packages we are able to solve our missing data issue.

![](titanic2.PNG)

## Model training
With the help of a ColumnTransformer, we build a LogisticRegression and SVM model with our dataset.

![](titanic3.PNG)

![](titanic4.PNG)



