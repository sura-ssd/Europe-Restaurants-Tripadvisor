# Data Pipeline and ETL Process with Power BI and PostgreSQL 

## About the dataset we used
TripAdvisor is the most popular travel website and it stores data for almost all restaurants, showing locations (even latitude and longitude coordinates), restaurant descriptions, user ratings and reviews, and many more aspects.

The website is well known for displaying user ratings and reviews for restaurants, hotels, b&b, touristic attractions, and other places, with a total word count of all reviews is more than 10 billion.

The TripAdvisor dataset includes 1,083,397 restaurants with attributes such as location data, average rating, number of reviews, open hours, cuisine types, awards, etc.

The dataset combines the restaurants from the main European countries.
Data has been retrieved from the publicly available website https://tripadvisor.com/.
All the restaurants from the main European countries have been scraped in early May 2021.

The dataset combines the restaurants from the main European countries.
## ETL Process
This project Practiced Python's Pandas library to extract, transform, and load the data into a PostgreSQL database.
  ### Visualization
  Power BI is used to visualize the meaningful insights by connecting to PostgreSQL database.
 ### Visualization list 
 ```
 - Count of poor, Count of terrible, Count of very_good, Count of total_reviews_count and Count of
excellent

- Count of avg_rating by country

- Count of features by restaurant_name

- Count of cuisines by country

- Count of total_reviews_count and Count of avg_rating by avg_rating

- Count of total_reviews_count by country

- What influences avg_rating to increase/decrease
```
### Visualization Description

The rating distribution bar chart would help understand customer satisfaction levels and identify areas for improvement. Low ratings indicate aspects to focus on.
The rating proportions by country stacked bar shows which markets have higher/lower satisfaction nationally. This points to where to prioritize efforts or tailor offerings.
Comparing average rating by country in a table facilitates targeting expansion efforts at locations with better Reviews or room for growth.
The tree map reveals which restaurant attributes like amenities are most common among highly rated establishments. This indicates qualities to emulate for new locations.
The cuisine popularity by country column chart aids decisions around what food types to offer in different markets based on cultural preferences.
A correlation between volume and quality displayed in the scatter plot suggests investing to improve ratings may boost viability through more reviews.
Tracking progress versus targets in the bullet chart helps gauge return on actions and adjust strategy based on rating performance milestones.
Total review counts by country bars help prioritize data gathering and market research in top reviewed regions for better understanding consumer needs locally.
Together these analyses inform data-driven decisions on product enhancements, market expansion, investment focus and brand strategy across borders and client segments. They optimize business decisions based on customer feedback trends.

## Members name
```
| No. | Name               | ID              |
| --- | ------------------ | --------------- |
|  1  | Surafel Seyoum     | DBUR/1204/12    |
|  2  | Bereket Kinfe      | DBUR/1205/12    |
|  3  | Temesgen Debebe    | DBUR/0888/12    |
|  4  | Yonas Million      | DBUR/3710/12    |
|  5  | Oliyad Lemma       | DBUR/0809/12    |
```
