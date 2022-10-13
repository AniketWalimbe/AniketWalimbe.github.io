# Project 2 Blog

## Purpose

One of the main purpose of the project was to develop functions to fetch the data by API and performing Exploratory Data Analysis by plotting various plots. 


## Project Flow

The first part of the project was to develop functions to retrieve data from Rest API Endpoints. For this, we have given 3 modifications for each function to contact the endpoints. Once, the function is developed, we retrieved the data for 4 companies and various prices related to their stocks. 

Here, we defined the scope of this project to investigate two types of companies: technical companies and financial companies. The specific companies we will focus on are:  Apple Inc. (AAPL) , Amazon Inc. (AMZN) , JPMorgan Chase & Co (JPM) , Wells Fargo & Co (WFC).  The first plot was   of the opening price for the stocks against the timestamp for doing various analysis like identifying the trends etc. Next, we created a new variable PriceVariation which is the difference between the highest and lowest price of the stocks of a company per day. The new variable represents the fluctuation range of the corresponding company. This variation is then plotted against the timestamp. We then calculated the summary statistics for the PriceVariation of all the four companies. Along with this, we also considered the Open Price and Close price variables and found out the mean, median, mode and IQR for both the variables.
We have then plotted a bar graph to show the count of keywords for one company wherein keywords is the categorical variable. A box plot was also made to reveal the closing price for Apple and Amazon Companies.  The scatter plot was also developed to investigate the relationship between open price and closing price. We plotted the Open Price and Close Price for a company against each other. Using the facet_wrap() function, we can see the subplots for 2 companies. 

## Challenges and Learnings

One of the most challenging parts of the project was to create contingency tables given the data we had. Since there was no categorical variables readily available, and hence we had to work around with the data. 
Working on this project helped me in learn how to fetch data from an API Endpoint and also made me more confident with plotting data. It also cleared my doubts regarding contingency tables enlightened me with the financial side since the data was more about stock prices and their variation. 

The github Repo for this project can be found [here](https://github.com/Charlie9898/ST-558-Project-2)

The resulting vignette can be found [here](https://charlie9898.github.io/ST-558-Project-2/)
