# Softwares Used- R, Data Source-Kaggle

# Movie-review-analytics

## Analysis on the impact of various predictors on box office collection.

## Data Cleaning

* We have various fields like actor/director name, reviews, gross revenue, movie title, language, budget and many more.

* Most movies were in color format and no black and white, so we dropped color. 
* Language had mostly English, so we dropped that. 
* The actor and director names were generally not common, so it did not make any sense to keep this field.
* We found out that genre has an impact on box office collection. We created a new column for each genre and assigned the value 0 or 1 if the movie belonged to that genre.
* After making few more changes, we finalized our data set
