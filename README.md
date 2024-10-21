Dataset
The dataset used in this project is the well-known Titanic dataset from Kaggle, which contains information on the passengers of the Titanic, including demographic details, passenger class, and survival status. The dataset can be found here.

The dataset is split into two parts:

train.csv: The training dataset used to build and validate models.
test.csv: The test dataset used for making final predictions.
Steps Involved
Data Cleaning:

Handled missing values for the Age, Embarked, and Fare columns.
Dropped the Cabin column due to excessive missing data.
Encoded categorical variables such as Sex and Embarked into numerical form for modeling purposes.
Exploratory Data Analysis (EDA):

Visualized the survival distribution and performed an in-depth analysis of how features like Age, Sex, and Pclass affected survival chances.
Women were found to have a much higher survival rate compared to men.
Feature Engineering:

Created dummy variables for categorical features (Sex and Embarked).
Scaled numerical features for machine learning models.
Modeling:

Trained multiple machine learning models:
Logistic Regression
Decision Tree
Random Forest
Support Vector Machines (SVM)
K-Nearest Neighbors (KNN)
Gradient Boosting
XGBoost
AdaBoost
Naive Bayes
MLP Neural Network
Evaluated the models using accuracy score and classification report.
Random Forest and Gradient Boosting achieved the highest accuracy of 82% on the test data.
Result Analysis:

Key insights were drawn, such as:
Women Survival Rate: 74.20%
Men Survival Rate: 18.89%
Models like Random Forest and Gradient Boosting performed the best, while simpler models like Naive Bayes and Decision Trees had lower accuracy.
