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
