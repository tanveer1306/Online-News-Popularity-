# Online News Popularity

#### There are 2 separate CSV files.Use the files accordingly.

## Need for the project
For content writers/editors, advertisers, content creators and website owners to make it easier for them to decide whether to publish an article or not and to make them understand the scope of improvement in the article.


## Scope
This project helps content writers and editors to be able to understand how popular their article would become prior to publication, which would provide a foresight to their articles popularity status and based on the results, improvisation of the articles can be done.


## Dataset Overview
Online News Popularity Data Set from UCI Machine Learning Repository.


## Problem Statement
The dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years. The objective is to build a model which can predict the number of shares of an online article at highest possible accuracy.


## Outcomes of Analysis
We can see that the feature variables have very low correlation to our target variable.Infact the highest correlated value is only 0.11.

Among the various models that were applied on the dataset, XG Boost regressor gave us the best MSE value of 0.667.

We can observe that the MSE value for any of the model applied lies within the range of 0.65 to 0.8. MSE can be low in situation of under fitting, where there are too many degrees of freedom available to Residual space and too few to the Regressor space.

The best R-squared value obtained is never above 20%.This value is quite low. A low R-squared value indicates that our independent variables is not explaining much in the variation of your dependent variable - regardless of the variable significance.

We can see that none of the features greatly impact the target variable.The prediction can be improved by taking into account other features which aren’t provided in the dataset.


## Recommendations

Key Preferences:
Increase in the Number of Keywords.
Words in the title between should be crisp (not too short and not too long).
Increase in the Number of Images.
Words in the content better kept minimal.
Restriction in the number of links to other articles up to 150.
Global Sentiment somewhere between neutral to positive polarity.
Lower the occurrence of negative words in the article content and title.
Length of the words in the content between 4-6 letters on average.
Articles Published in the weekend are shared more.

#### Data Channel:
Editors may want to consider the importance of channels when it comes to popularity and required emphasis must be given.
Lifestyle > Social Media > Technology > Business > Entertainment > World.

#### Time of Publication:
Articles are published in certain days are shared more than others.
Saturday > Sunday > Monday > Friday > Tuesday > Thursday > Wednesday.
We can see that the weekend published articles are usually shared more.

## Limitations

Our model focuses on the content part of the article more and therefore misses out on the other factors such as reader’s attributes, time relevance of the article’s subject which could also heavily influence the shares of the articles.

Reader Demographics such as Age, Location could vary with respect to the kind of articles (content, channel) they are sharing more which we lack in our dataset and therefore model.

The model is quite low in the precision point of view in predicting the number of shares and subsequently it tends to the increase in the error in the predicted values.

## Future Developments
Various other variables on the reader’s front such as reader demographics, socio-economic features such as Age, Income, Location, Career and time period relevance of the article’s news can be an influencing factor in the articles which he chooses to share more. These variables help us in better reader/customer segmentation and further help us in understanding and predicting the shares better.
