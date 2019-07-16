# Income Prediction

Here, we are dealing with a Binary Classification problem at hand wherein the main objective is to predict whether an individual's income is >$50K or <=$50K. So, the reponse variable Income has two categories here -- 'Yes' if the salary is >$50K and 'No' if the salary is <=$50K.

Main steps involved in this case study:

1) Business Problem Understanding

2) Hypothesis generation

3) Reading the data

4) Understanding the data (Exploratory Data Analysis)

    - Univariate Analysis

    - Bivariate Analysis
5) Missing Values and Outliers treatment

6) Feature Engineering

7) Evaluation metric for this Classification Problem

8) One-hot encoding

9) Modeling and Evaluation

    - Logistic Regression

    - Random Forest

    - XGBoost
    
Important insights obtained were:

• Around 70% people belong to private WorkClass.

• Majority of the people i.e. around 32% have an education atleast until HS-Grad while around 22% and 16% have gone to some college and have a bachelors degree respectively.

• Around 46% people have a MaritalStatus as Married-civ-spouse and around 33% of the people are Never-married . A very close to 13% people are Divorced as well.

• The most common occupations observed are Prof-specialty (13%), Craft-repair (12.5%), Exec-managerial (12.2%), Adm-clerical (11.4%), Sales (11.2%) and Other service (9.8%).

• 41% are husbands while around 26% are Not-in-family.

• Around 67% are Male and 33% are Female.

• A whooping 90% people are from the United States.

• People in the self-emp-inc and Federal-gov WorkClass have income >50K. It doesn't quite match our assumption made in the hypothesis generation.

• People having Doctorate, Prof-school and Masters earn higher income as compared to other categories and also, it completely matches our assumption.

• Married-AF-spouse and Married-civ-spouse earn higher income as compared to other MaritalStatus.

• People having Exec-managerial and Prof-specialty as their occupation earn more which somehow matches our assumption as well.

• Husband and Wife are likely to earn more than other categories in Relationship variable.

• Male tend to dominate over Female in earning an income of >50K.

Apart from this, the case study focuses perfectly on dealing with issues such as Skewness in a variable, overfitting, multicollinearity, ouliers as well as transformations.

Three algorithms namely Logistic Regression, Random Forest and Extreme Gradient Boosting (XGBoost) have been implemented in this case study. XGBoost has been proven to give highest F1-score among the three and hence it's parameters have been hypertuned.

An overall F1-Score of almost 90% was obtained.




