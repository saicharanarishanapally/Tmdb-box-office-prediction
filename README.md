#Tmdb box office prediction
#Exploratory Data Analysis

##Exploratory data analysis for:

   1. Missing values
   2.Distribution for numeric features
   3.Time series data analysis
   4.Median revenue for original_language, status, genres, production_companies and production_countries.
#Feature Engineering

##Feature engineering for:

   1.Data filling (revenue, budget, runtime and release_date)
   2.inflationBudget
   3.popularity mean year
   4.ratio of Budget to runtime,ratio of Budget to popolarity,budget year ratio
   5.releaseYear popularity ratio
   6.no. of words on title,no. of words on overview,no. of words on tagline
   7.mean of runtime By Year,mean of Popularity By Year,mean of Budget By Year,median of Budget By Year
#Prediction Model and respective rmse
#Comparision between all models 
 
 MODEL          |  RMSE
 ---------------|----------
 Randomforest   |  0.65
 Lightgbm       |  0.66
 XGBoost        |  0.58
