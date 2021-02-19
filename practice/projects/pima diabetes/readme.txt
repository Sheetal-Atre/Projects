A population of women who were at least 21 years old, of Pima Indian heritage and living near Phoenix, Arizona, was tested for diabetes according to World Health Organization criteria. The data was collected by the US National Institute of Diabetes and Digestive and Kidney Diseases.

 

For this course, you have been provided with a cleaned up version of that data, containing 392 observations in the following file.
Also, you can refer to the following data dictionary to understand the variables.

Answer the questions below by running the logistic regression model on your machine.

 

Load the data set given above in Python. It has already been cleaned, so you don’t have to do any EDA on it or remove any missing values or outliers. Also, it has no categorical variables, except for the target variable, i.e. diabetes. So, you do not have to create any dummy variables here.


Standardise Variables

First, you will have to split the dataset into training and testing data sets, in the ratio 70:30. Use a random state of 100 for the splitting and split the function using the train_test_split command, or else your answers will not match the answers here.

Now, there is still one task left. Since there are 7 continuous variables in the dataset, you do have to scale all of them.

After standardising all 7 continuous variables, which one of them has the highest median value?

Plasma_Glucose

Diastolic_BP

Triceps

BMI
