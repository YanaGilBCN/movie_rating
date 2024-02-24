# Movie Rating

This repository contains movie-related data pulled from IMDB, including details about movies released in 2018 and their ratings.

## Files

- **title_basics_2018.csv:** Contains information about movies released in 2018, including the title, original title, release year, runtime, and genres.
- **title_ratings.csv:** Provides ratings for all movies, including the average rating and the number of votes.

## Questions

1. **Number of 2018 Comedy Films:** According to the provided dataset, how many 2018 films were categorized as a Comedy?

2. **Highly Rated 2018 Films:** According to the provided dataset, how many 2018 films got a score of 8.0 or higher? (Note that this will require joining the two datasets together)

3. **Best Film of 2018:** What was the best film of 2018?

4. **Audience Preference:** Do audiences prefer longer films, or shorter films? You may choose to simply outline your methodology to approach this problem.

## Dataset Details

### title_basics_2018.csv

- **tconst:** Alphanumeric unique identifier of the title
- **primaryTitle:** The more popular title / the title used by the filmmakers on promotional materials at the point of release
- **originalTitle:** Original title, in the original language
- **year:** Represents the release year of a title
- **runtimeMinutes:** Primary runtime of the title, in minutes
- **genres:** Includes up to three genres associated with the title

### title_ratings.csv

- **tconst:** Alphanumeric unique identifier of the title
- **averageRating:** Weighted average of all the individual user ratings
- **numVotes:** Number of votes the title has received

## Methodology

### 1. Data Preparation and Exploration

- **Importing Libraries:** Begin by importing necessary libraries such as Pandas, Matplotlib, and Seaborn for data manipulation and visualization.

- **Exploring Dataset:** Use Pandas to read the provided datasets and understand their structure. Ensure data consistency and identify any missing values.

### 2. Analyzing Comedy Films in 2018

- **Counting Comedy Films:** Utilize the 'title_basics_2018.csv' dataset to identify and count all movies categorized as Comedy in 2018.

- **Data Filtering:** Filter the dataset to isolate Comedy films and further analyze the occurrence of Comedy as a single genre or in combination with others.

### 3. Evaluating Highly Rated Films in 2018

- **Joining Datasets:** Merge the 'title_basics_2018.csv' and 'title_ratings.csv' datasets on the unique title identifier ('tconst').

- **Filtering Criteria:** Extract movies released in 2018 with a rating of 8.0 or higher.

- **Determining the Best Film:** Establish criteria for the "best" film, considering factors like average rating and number of votes. Identify the top-rated film meeting the defined criteria.

### 4. Assessing Audience Preference for Film Length

- **Defining Metrics:** Establish a metric for audience preference, combining average rating and number of votes.

- **Exploratory Analysis:** Explore the relationship between film length (runtime) and audience ratings through visualization (scatter plots) and correlation analysis.

- **Grouping Films:** Categorize films based on runtime into short, medium, and long categories using industry standards or quartiles.

- **Weighted Rating Calculation:** Calculate a weighted rating for each film category based on the number of votes.

- **Comparative Analysis:** Compare mean average ratings between short, medium, and long films using statistical tests like ANOVA. Conduct regression analysis to further explore the relationship between film duration and ratings.

- **Conclusions:** Draw conclusions from the analysis, considering any limitations such as genre effects on audience preference.

## Summary

This methodology outlines a structured approach to analyze film data, focusing on Comedy films in 2018, identifying highly rated films, and evaluating audience preference based on film length.

# movie_rating
