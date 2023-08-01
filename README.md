# Yelp-Data-Analysis
The Yelp dataset is a collection of user-generated reviews and associated data for businesses in various cities. The data includes information such as the business name, category, location, rating, user ID, and review text for each review. This project aims to analyze patterns and trends in consumer behavior, business performance, and geographic locations. Additionally, we will explore relationships between different variables, such as ratings, reviews, and business categories, to gain insights and make informed decisions in various industries.

Description of Data Variables:
business_id: A unique identifier for each business in the dataset.
business_categories: A list of categories associated with the business.
business_city: The city where the business is located.
user_id: A unique identifier for each user who has written a review.
text: The text of the review.
stars: The user's rating towards the business.
useful: The number of times the review was voted as useful.
date: The date the review was posted.

## Check and Remove Missing Data
We will write a Python code snippet that checks for missing values in each column of the dataset. If any missing values are found, we will display the names of the columns with missing values and their corresponding number of missing values. We will also print the length of the data before removing the missing data.

## Check and Remove Invalid Data
Next, we will remove any rows that contain at least one missing value and output the length of the resulting cleaned dataset. After that, we will remove any rows that contain invalid values with either "#NAME?" or "#VALUE!" in the business_id and user_id columns and output the length of the resulting cleaned dataset.

## Random Subset Selection of Yelp Businesses by City
In this part, we will select a random subset of 10 cities from the dataset and extract all the rows corresponding to businesses located in those cities. This random subset selection will allow us to perform exploratory data analysis on a smaller, more manageable subset of the data.

## Select Random Subset of Cities
We will use the random.sample() function to select 10 random cities from the list of unique cities. Before selecting the cities, we will set the random seed to 42. We will then extract all rows corresponding to businesses in these 10 cities and print the length of the resulting sample data.

## Descriptive Statistics on Sample Data
In this part, we will compute summary statistics for the stars column of the sample data, including count, mean, standard deviation, minimum, and maximum values. Additionally, we will calculate the number of unique businesses for each city in the sample data and explore the number of unique users who have rated each business category and business ID combination.

## Summary Statistics for stars Column
We will compute summary statistics for the stars column of the sample data.

## Number of Unique Businesses per City
We will calculate the number of unique businesses for each city in the sample data and compute summary statistics for the count column.

## Number of Unique Users per Business Category and ID
We will explore the number of unique users who have rated each business category and business ID combination in the sample data. The resulting dataframe will have three columns: business_categories, business_id, and count. We will compute summary statistics for the count column.

## Plotting and Analysis
In this part, we will explore the distribution of each variable and examine the correlation between business_city, useful, business_categories, or other variables, and the stars column in both the cleaned dataset from Question 1.1 and the sampled dataset from Question 2.1. We will use various visualization techniques, such as box plots, to compare the distributions and identify any patterns or trends. For example, we may investigate whether some cities tend to provide higher stars than others.

## Challenges and Observations
Analysis and observations in this project are open-ended, requiring critical thinking and data analysis skills. We will draw our own insights and conclusions based on the data. The process fosters critical thinking, ownership of learning, and a deeper understanding of the Yelp data.

## Conclusion
This project aims to analyze Yelp data to gain insights into consumer behavior, business performance, and geographic patterns. We will preprocess the data, clean any missing or invalid data, and perform exploratory data analysis to understand the dataset better. Our analysis and observations will help us draw conclusions and make informed decisions based on the data.
