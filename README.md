# office-episode-ratings-predictor
Machine learning project.

Intended model: Regression

OLS linear, ridge or lasso? 

Stepwise reduction of statistically insignificant variables

## Intended explanatory variables

Response variable: imbd_rating

Adjusted imbd_rating
(or weighted imbd_rating by total_votes)

(or distance from average rating and average votes
is a scaling factor)

From the original data:
* Categorical: Season
* Categorical: Director
* Categorical: Writer
* Continuous: Total votes weighting something?
* Continuous: n_lines (normalised?)
* Continuous: n_directions (normalised?)
* Continuous: n_words (normalised?)
* Continuous: n_speak_chars (normalised?)
* Categorical: On each main_char
* Categorical: On each pairing of characters
* Categorical: Full combinatorical enumeration of pairings and triples, etc...

Not from original data:
* Categorical: Are Jim and Pam currently dating in this episode?
* Categorical: Are Dwight and angela currently dating in this episode?
* Categorical: Jan
* Categorical: Calendar season (Summer, Winter, Spring, Autumn)
* Continuous: Number of guest stars

https://www.kaggle.com/code/nehaprabhavalkar/the-office-tv-series-part-1-eda-using-plotly/notebook



## Other queries

* PCA? 
* Missing data? 
* Data cleaning/preproccesing?
* Feature engineering?
?



