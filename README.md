Advancements in machine learning have made credit card default risk prediction a relatively easy task.
With respect to machine learning, default risk prediction is essentially a binary classification problem
with two possible outcomes - ‘Defaulter’ (1) and ‘Not a Defaulter’ (0). Binary classification can be
solved using different models such as Logistic Regression, Naive-Bayes or Support Vector Machines
(SVM). Below are the major steps we have followed in implementation of this project:

● Exploratory Data Analysis (EDA) - Plotting different graphs to visualize the credit limit range
and distribution, distribution of other features and multivariate analysis.

● Correlation Matrix - Plotting heat map to visualize the correlation between each of the features
with themselves as well as with the value to be predicted

## Data wrangling
○ Conversion of data into numeric data types to be able to perform operations on them
○ Renaming columns to make sense
○ Dropping unnecessary columns
○ One-hot/binary encoding on the nominal features of the dataset - education and marital
status
○ Scaling of data - Using standardization to limit the values between [1, -1] and make their
mean approximately zero.

● Train-Test split - Data has been split into two using the sklearn_model selection train_test_split
function with a train size of 0.8 i.e., training set is 80% of the entire data for Logistic Regression
and 3% for SVM

● Computation of results using inbuilt packages to see which model performs best - Logistic
Regression, Naive Bayes, KNN or Support Vector Machine.

## Model building by writing own code
○ Custom Logistic Regression model
○ Custom Soft Margin SVM model
