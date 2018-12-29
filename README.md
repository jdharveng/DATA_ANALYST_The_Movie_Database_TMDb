# DATA_ANALYST_The_Movie_Database_TMDb
Analysis of TMDb dataset containing 10000 movies
## by Jérôme d'Harveng


## Dataset

> For this analysis, the TMDb dataset has been choosen (originally coming from Kaggle).
This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

> **Questions Analysed**: After inspecting and cleaning this dataset, we'll focus on 2 aspects:
> 1. What are the properties of high earning movies? 
> 2. Which genres of movies are produced the most year after year?

## Limitations
> To run this analysis, some limitations are important to be mentioned as for example no Machine
Learning, Inferential Statistics or Statistical Tests were used.

> ** Limitations** : Revenue_adj and budget_adj, have a lot of zeros, from the 10866 lines, 7012 lines had to be dropped (> 70% of the dataset). 
This have an impact on the representativeness of the the remaining dataset in regards to the population.

## Summary of Findings

> After analysing the cleaned dataset TMDb, some observations could be made (taking into account the limitations exposed in 'First Comments').
> ** Q1 - Properties of High Earning Movies:**
Using scatterplots and verifying with Pearsons Coefficients no linear correlation could be found between:
vote_average vs earnings_adj nor for release_year vs earnings_adj.

> After having separated High Earning Movies of the Low Earning Movies (based on the mean earning_adj), we could notice that **on the average**:
> 1. High Earning movies get higher vote_averages
> 2. High Earning movies last longer
> 3. High Earning movies were released earlier


> ** Q2 - Which genres of movies are released more year after year:**
After separating the different genres in separated column and putting this in graph, we could notice that:
> 1. Most genres saw their amount of movies released increase year after year
> 2. Four genres get the most increases: Drama, Comedy, Thriller and Action
