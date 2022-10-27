# Online News Popularity-

#### There are 2 separate CSV files.Use the files accordingly.

### Need for the project
For content writers/editors, advertisers, content creators and website owners to make it easier for them to decide whether to publish an article or not and to make them understand the scope of improvement in the article.

### Scope
This project helps content writers and editors to be able to understand how popular their article would become prior to publication, which would provide a foresight to their articles popularity status and based on the results, improvisation of the articles can be done.

### Dataset Overview
Online News Popularity Data Set from UCI Machine Learning Repository.

### Problem Statement
The dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. The objective is to build a model which can predict the number of shares of an online article at highest possible accuracy.

### Outcomes of Analysis
We can see that the feature variables have very low correlation to our target variable.Infact the highest correlated value is only 0.11.

Among the various models that were applied on the dataset, XG Boost regressor gave us the best MSE value of 0.667.

We can observe that the MSE value for any of the model applied lies within the range of 0.65 to 0.8. MSE can be low in situation of under fitting, where there are too many degrees of freedom available to Residual space and too few to the Regressor space.

The best R-squared value obtained is never above 20%.This value is quite low. A low R-squared value indicates that our independent variables is not explaining much in the variation of your dependent variable - regardless of the variable significance.

We can see that none of the features greatly impact the target variable.The prediction can be improved by taking into account other features which aren’t provided in the dataset.
