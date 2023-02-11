# **Project-1-Team-8**
# **Netflix Movies and Shows Analysis - Group 8**
By: Satya Sakuntala NagaSravya Mattapalli, Zack Crowley, Edith Lotterman and Kevin Ybarra  

## Project Description:

- Our project analyzes which type of content has the greatest viewership over the time period of 6/15/21 to 11/1/22 on the Netflix streaming service. This project attempts to find which movies and TV shows are most popular and other factors that drive increased viewership. Specifically, movies and shows on the Netflix Top Ten lists.

1. Impact of genre vs English and Non-English movies and TV Shows
2. Which TV Shows and Movies drive increased viewership over this period of time
3. Impact of popularity between English and Non-English Movies and TV Shows

## Research Approach:

1) Identify Data Sources for all required analysis. Data sources below:

- “Netflix Movies and TV Shows” dataset from Netflix.
- Merged with “Netflix Titles” dataset from Kaggle to populate specific information for each movie and TV show.
- API call from OMDB to fill in all “NaN” values that were not in the “Netflix Titles” merge.
- The data provided captures from the week of 6/15/21 to 11/1/22.

2) Loading and standardizing all inputs identified above into pandas dataframes and producing working .csv files that enabled all data visualizations.

- See team8_netflix_proj1_dataCleaning.ipynb for cleaning
- See team8_netflix_proj1_Analysis.ipynb for analysis


## Process:

We used the "Netflix Movies and TV Shows Top Ten Lists" as our main dataset from Netflix then merged it with "Netflix Titles" from Kaggle to gather our content information. We then utilized an OMDB API call to fill all NaN value types to fill the gaps. After all data had been merged, we dropped what remained of the NaN values for our completed dataset. Countries, ratings, and genre columns were cleaned. Finally, we created columns to get the count of each genre as it appeared in the string.

## Exploratory Analysis

- After combining all datasets we were left with 644 unique titles which made up about 2069 rows of data.
- We found that 37% of titles across all categories stays in the Top 10 for 1 week before falling off.
- Most of Netflix hits on the Top 10 do not remain popular for a long time.
- Only 4 titles have remained in the Top 10 for more than 20 weeks, which makes up 1.6% of all the Netflix titles given for this period of time.

## Project Description:

- Our project analyzes which type of content has the greatest viewership over the time period of 6/15/21 to 11/1/22 on the Netflix streaming service. This project attempts to find which movies and TV shows are most popular and other factors that drive increased viewership. Specifically, movies and shows on the Netflix Top Ten lists.

1. Impact of genre vs English and Non-English movies and TV Shows
2. Which TV Shows and Movies drive increased viewership over this period of time
3. Impact of popularity between English and Non-English Movies and TV Shows

## Research Approach:

1) Identify Data Sources for all required analysis. Data sources below:

- “Netflix Movies and TV Shows” dataset from Netflix.
- Merged with “Netflix Titles” dataset from Kaggle to populate specific information for each movie and TV show.
- API call from OMDB to fill in all “NaN” values that were not in the “Netflix Titles” merge.
- The data provided captures from the week of 6/15/21 to 11/1/22.

2) Loading and standardizing all inputs identified above into pandas dataframes and producing working .csv files that enabled all data visualizations.

- See team8_netflix_proj1_dataCleaning.ipynb for cleaning
- See team8_netflix_proj1_Analysis.ipynb for analysis


## Process:

We used the "Netflix Movies and TV Shows Top Ten Lists" as our main dataset from Netflix then merged it with "Netflix Titles" from Kaggle to gather our content information. We then utilized an OMDB API call to fill all NaN value types to fill the gaps. After all data had been merged, we dropped what remained of the NaN values for our completed dataset. Countries, ratings, and genre columns were cleaned. Finally, we created columns to get the count of each genre as it appeared in the string.

## Exploratory Analysis

- After combining all datasets we were left with 644 unique titles which made up about 2069 rows of data.
- We found that 37% of titles across all categories stays in the Top 10 for 1 week before falling off.
- Most of Netflix hits on the Top 10 do not remain popular for a long time.
- Only 4 titles have remained in the Top 10 for more than 20 weeks, which makes up 1.6% of all the Netflix titles given for this period of time.

## Dataset Overview

- When exploring the data, we found that the most movies and TV shows consisted on the genre "drama".
- Against our expectations, we found that Non-English TV shows stayed on their respective Top 10 lists than English TV shows in the top 3 genres.

## Additional Overview

- After cleaning the data, we were left with a total of 644 unique titles that were broken down into 4 categories Non-English and English movies and TV shows.
- That data shown has a variance of 171 movie titles and 13 show titles with English content have more.

# Questions Answered

1) The most popular genres are drama, comedy, action, crime, romance and family with drama TV shows being the most popular.
2) The 2 TV shows that stayed in the Top 10 the longest are “Yo soy Betty, La Fea” and “Squid Games”.
- The 2 Movies that stayed in the Top 10 the longest are “Red Notice” and “Through My Window”.
3) After performing Chi-Square tests, the data indicates that the relationship between Non-English and English movies and TV shows is indeed different.
