# Tmdb box office prediction
# Exploratory Data Analysis
# Problem
In this competition, you're presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.
## Exploratory data analysis for:

   1.Missing values
   
   2.Distribution for numeric features
   
   3.Time series data analysis
   
   4.Median revenue for original_language, status, genres, production_companies and production_countries.
# Feature Engineering

## Feature engineering for:
   1.Data filling (revenue, budget, runtime and release_date)
   
   2.inflationBudget
   
   3.popularity mean year
   
   4.ratio of Budget to runtime,ratio of Budget to popolarity,budget year ratio
   
   5.releaseYear popularity ratio
   
   6.no. of words on title,no. of words on overview,no. of words on tagline
   
   7.mean of runtime By Year,mean of Popularity By Year,mean of Budget By Year,median of Budget By Year
# Prediction Model and respective rmse
# Comparision between all models 
 
 MODEL          |  RMSE
 ---------------|----------
 Randomforest   |  0.65
 Lightgbm       |  0.66
 XGBoost        |  0.58
