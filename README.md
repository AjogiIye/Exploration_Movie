# (TMDb_Movies)

### Project: Exploration of TMDb Movie Dataset


## Table of Contents

#### . Introduction

#### . Limitations

#### . Data Wrangling

#### . Exploratory Data Analysis

#### . Conclusion



## Introduction

This project entails the investigation of a dataset taken from the Movie Database (TMDb), "a community-built movie and TV database "(https://www.kaggle.com/tmdb/tmdb-movie-metadata). Apiece row links to a movie and includes a range of data about each film. Pertinent data to be used in the subsequent analysis include the following variables: 

original_tile

genres

release_date

release_year

In this report, I explore the following question as stated below:

What Year has the highest release of movies? 

What Movie is with highest and lowest profit?  

Which is the Highest Budget movie and Lowest Budget Movies?

What Movies generated Highest Revenue and Lowest Revenue?

Which is the Longest Runtime Movie and Shortest Runtime Movie?

Which is Highest Rated movie and Lowest Rated Movie?

Which Year has Highest Profit Rate?

What Movie duration is liked by customers based on popularity?

Which is Year by Year Average Runtime of Movies?

What relationship can be established between variables such as revenue, popularity, budget, runtime, and profit? 

Which Movie Genre has the Highest Release?

Can we provide the list of the most popular genres from year to year?

Can we provide the list of the top 20 directors that direct maximum movies?

Throughout my analysis, profit (as calculated by subtracting each film's budget from its revenue) will be the dependent variable, while release year, release date, budget, and genre will be the independent variables.


## Limitation

1. There is no normalization or exchange rate or currency conversion considered in the course of this examination thus my analysis is limited to numerical values of revenue 
2. During the data cleaning process, I split the data separated by "|" into a list for analysis during the data exploration stage. This increased the time taken for computing the results.
3. Dropping missing or Null values from variables of my interest might skew my analysis and could skew inadvertent bias toward the relationship being analyzed etc.


## Data Wrangling

In this part of the project, I loaded the dataset using panda’s library. I checked for quality issues, and tidiness issues, and afterward clean the dataset for analysis. All procedures taken to achieve excellent data wrangling were explicitly justified and documented 

#### Command Used

I deployed these commands: .shape, .info (), .describe(), .isnull() and .duplicated  which enabled me to have a quick overview and inspection of the dataset

#### Valuation

##### Quality Issues

The dataset contains Null values
The datatype for the release date is a string; this should be converted to DateTime 
There are duplicates that need to be drop
There are dependent and independent variables in the columns

##### Tidiness Issues

The genre column has more than one variable

#### Data Cleaning

I explicitly addressed the quality issues and tidiness issues as listed in the valuation


## Exploratory Data Analysis

I performed the exploratory data analysis which led to my conclusions for this project


## Conclusion

In the first section, I examined the year with the highest release of movies. I made my analysis based on the values of 'release_year' and the number of movies. I was able to establish the fact that the year with the highest release of movies turned out to be 2014 with 700 movies.

Furthermore, I analyzed the popularity of movies based on runtime and found out that movies with an average runtime of 100min had the highest popularity as compared to the ones with a runtime of over 125min.
