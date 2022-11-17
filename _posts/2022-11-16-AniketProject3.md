# ST558 Project 3 

## Purpose 

The main purpose of the project is creating predictive models and automating Markdown reports. The dataset used for the project is [online news popularity data set](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity) which summarizes a heterogeneous set of features about articles published by Mashable in a period of two years.
The goal was to create models for predicting the number of shares

## Project Workflow 

The very first step of the project was reading the data and combining the seven different columns for workdays together as a single column and then, removing the non-predicting variables. 
Once this was done, the data was divided into training and testing set and EDA was carried out on the training dataset. A few basic summary statiistics and plots were created along with contingency tables to understand the behaviour of different variables with respect to the response variable. For the contingency table, we divided the title subjectivity rate into 3 different categories namely high, medium and low and classified the data. We then plotted the correlation between the numeric variables to decide which variables should be shortlisted for creating models for prediction. 

After selecting the variables, we created 3 linear models, random forest model and a boosted tree model on the training dataset and then tried to predict based on the testing dataset.
To determine the best models, we compared the RMSE values of all the models and the model with the lower RMSE value was then selected. The final step involved automating the generation of analysis report for various different channels for which we firstly create a set of parameters, which match with 6 channels and then read the parameter and subset the data with the specified channel.

## Challenges and Learnings 

One of the most challenging part of the project was to determine the variables to be selected for creating the models. That is also one of the things I would do differently since, the RMSE values for the models created are very high. Maybe, better selection of models can improve the prediction of the response variable.
On the other hand, automating and building models on a huge dataset was a big plus which makes me comfortable to work with large amount of data now. 

The github repo to the project can be found [here](https://github.com/shaoyucherish/Project3)

The link to the rendered file can be found [here](https://shaoyucherish.github.io/Project3/)

