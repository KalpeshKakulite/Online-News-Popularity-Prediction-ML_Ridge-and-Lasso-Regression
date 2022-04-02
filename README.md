# Online-News-Popularity-Prediction-ML_Ridge-and-Lasso Regression

****Problem Description******
**Importance of online news****   The consumption of online news is expediting day by day due to the extensive adoption of smartphones and the rise of social networks. Online news content includes various key properties like it is easily produced, it is small in size, its lifespan is short and the cost is low. Such qualities make news content more effective to be consumed on social sharing platforms. More interestingly, such content can capture the eye of a signiﬁcant amount of internet users within a brief period of time. As a result, the main target on the analysis of online news content, like predicting the recognition of story articles and demonstrating their decay of interest over time, has significantly increased since it has so many practical meanings.  

**Why news popularity prediction?**
There are multiple areas of applications for online news popularity prediction. One of these includes gaining better insights into the audience consuming online news content. Consequently, it increases the ability of news organizations to deliver more relevant and appealing content in a proactive manner. Also, the company can allocate resources more wisely to prepare stories over its life cycle. Moreover, prediction of news content is also beneﬁcial for trend forecasting, understanding the collective human behavior, advertisers to propose more proﬁtable monetization techniques, and readers to ﬁlter huge amounts of information quickly and efﬁciently.

**Steps Involved:**

1. Importing Libraries
2. Loading and Analysing the DATA
3. Data Cleaning & Manipulation
4. Handling Outliers and Null Values
5. Exploratory Data Analysis (EDA): Univariate and Bivariate Analysis 
6. Splitting the Data into Training and Testing Sets
7. Pricipal Component Analysis (PCA)
8. Model Building: 
 a)  Baseline Model-Logistic Regression
 b) Model Building using  Ridge Regression
 c) Model Building using Lasso
9. Making Predictions
10. Model Evaluation

**Libraries Used:**
1. NumPy as np
2. Pandas as pd
3. Matplotlib.pyplot as plt
4. Seaborn as sns
5. Ridge and Lasso
6. from sklearn.model_selection import GridSearchCV
7. GradientBoostingClassifier 

**Model Evaluation:** 
1. **Logistic Regression:**

**Train metrics**
explained_variance:  0.0219
r2:  0.0219
MAE:  3130.6311
MSE:  147034937.4855
RMSE:  12125.7964

**Test metrics**
explained_variance:  0.0211
r2:  0.0211
MAE:  3112.5323
MSE:  141273235.2537
RMSE:  11885.8418

2.  **Ridge Regression **
 
**Train metrics**
explained_variance:  0.0219
r2:  0.0219
MAE:  3122.7682
MSE:  147041530.3931
RMSE:  12126.0682

**Test metrics**
explained_variance:  0.0214
r2:  0.0214
MAE:  3104.2359
MSE:  141230476.1353
RMSE:  11884.0429

3. **Lasso Regression**

**Train metrics**
explained_variance:  0.021
r2:  0.021
MAE:  3108.6651
MSE:  147172602.7921
RMSE:  12131.4716

**Test metrics**
explained_variance:  0.0214
r2:  0.0214
MAE:  3088.8122
MSE:  141231418.9238
RMSE:  11884.0826
