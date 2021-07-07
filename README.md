# Melbourne-house-price
Personal Data Science project for predicting house prices in Melbourne using 2016-17 dataset from Kaggle (https://www.kaggle.com/dansbecker/melbourne-housing-snapshot).

## house_price_preprocessing.ipynb
- Preprocess data and refine dataset by removing multicollinearity, removing outliers, etc.

## house_price_tosql.ipynb
- Set up MySQL database to store the cleaned dataset.
- Setting up a database for such a not-large dataset is not necessary but this step was added for my practice in setting up databases and performing ETL in Python.

## house_price_EDA_FeatureEngineering.ipynb
- Fetch data from MySQL database and perform Exploratory Data Analysis and engineer new features with more data from web scraping.
 - Future improvement: I manually created a new feature by computing each house's distance to its closest train station in Melbourne. Turns out that there is the `GeoPandas' library that can do such tasks easily. Remember for future projects!
- Conveniently visualise house prices in Melbourne graphically using Google Maps API. 

## house_price_modelDevelopment.ipynb
- Using the cleaned, final data, try out various machine learning models and compare the performance in predicting house prices on test set.

 
 
 
 
