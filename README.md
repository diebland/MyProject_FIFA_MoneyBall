# Project_FIFA_Money_Ball 


### Objectives of the project :

 - Perform an end-to-end analysis and apply statistical or machine learning techniques

 - Rank footbal players by market value.

 - Highlight the top players for their outstanding performances over a discrete season.

 - Implement machine learning model : create the best prediction of the market value of the players

### Project step by step :
      1 - cleaning the dataset 
      2 - exploring and visualizing the datas to determine best market value players and performant players  
      3 - predicting the market value of the players using linear regression models

I have 

I have decided to run the linear regression model on two datasets :
    1-  a large dataset preserving most of the dataset. The model has been run before and after preprocessing of the datas. 
        I have used a standardization method to preprocess the datas.
    2-  Second I have selected the following features : age, potential, base stats, international reputation, reactions, pace, shoots, passing, dribbling, defense and physical.
    
I choose the features based on domain knowledge and analysis of datas.
I would like to know if we can determine the value of a player based on some general indicators and on his football skills. 

The first run will be done before preprocessing (a).
Then I will use a bocxcox transformation and run the linear regression on the same dataset. (b)

###  Analysis

The best R2 score obtained is on a reduced dataset after the boxcox transformation. (R2 = 0,84)

Based on this result, we may say that the market value of a football player can be determined by few features such as performance, potential, age and are not based on complex combination of variables.


#### Documentation
 * All the datasets as well as the graphs can be found on the repository
 * Sources (link to the source of the data https://www.kaggle.com/ekrembayar/fifa-21-complete-player-dataset)
 * List of libraries (with a link to the documentation)

https://scikit-learn.org/stable/index.html
https://docs.scipy.org/doc/scipy/reference/index.html
https://pandas.pydata.org/
https://numpy.org/doc/
https://matplotlib.org/3.1.1/
https://seaborn.pydata.org
