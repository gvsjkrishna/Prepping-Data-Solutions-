# Analytics - Technical Interview

In this section of the interview, you will be assessed on your ability to perform several analytical tasks. We will allow you to complete the tasks using the tools or languages you are most comfortable. To perform well on this task, you will demonstate competence in the following areas:

* understanding entity relationships in a database
* merging data from different tables
* filtering data to relevant subsets
* calculating aggregations and descriptive statistics
* visualizing data
* building a predictive model and making predictions on unseen data

It will be pretty difficult to complete all questions in the allotted time. Your goal is not to speed through the answers, but to come up with answers that demonstrate your knowledge. It's more about your thought process and logic than getting the right answer or your code.


## Getting Started

The data for this exercise is a small SQLite database containing roughly a dozen tables. If you are not familiar with the SQLite database, it uses a fairly complete and standard SQL syntax, but does not have many advanced analytics functions. Consider it just a remote datastore for storing and retrieving data. 

![](db-diagram.png)

## Data Wrangling (20 minutes)

1. How many different customers are there?
2. How long is the longest track in minutes?
3. Which genre has the shortest average track length?
4. Which artist shows up in the most playlists?
5. What was the most popular album among these customers?


## Statistics & Predictive Modelling (20 minutes)

1. What is the correlation between the length of a track and its price?
2. Do any seasonal patterns occur in purchases (invoices)?
3. How would you tell whether a new Rock song is an outlier in terms of track length?
4. We want to build a recommendation service for our customers. 
    * What features might be important for predicting whether a customer is likely to purchase a track? 
    * Create a simple model based on those features and evaluate it's performance. 
    * How much did those features individually contribute to the predictions of your model?
    * How would you explain your model to a Product Manager? To the Sales team?
    * What next steps would you take to improve the predictive performance of your model?


## Data Visualization (10 minutes)

1. Prepare a plot(s) that effectively illustrates the variation of track length by genre.
2. Prepare a plot(s) that summarizes sales by month. *Bonus opportunity: add a trend line.*
3. Take a look at the following plot from the Economist on the relationship between corruption and development of countries. 
    * What aspects of the plot work well?  
    * What would you change about it to be more effective?

![](https://cdn.static-economist.com/sites/default/files/20111210_WOC210.gif)


