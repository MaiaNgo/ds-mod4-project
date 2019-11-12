
### Mod 4 Project - Building Model to Predict House Price
The purpose of this project is to use Zillow's historical house sale data to build a machine learning data model that can help to predict future house sale price in 3 years. From that predictive model we can forecast the future prices and select the best 5 zipcodes that have best growth for investment recommendation.

#### Process
The process that I have done for this project are as following:
- Load and clean the data from Zillow
- Perform EDA to understand the data and examine the stationarity, seasonality and trending of the data
- Use auto_arima to perform grid search to find the best-fit model for each zipcode data
- Perform train/test split to predict the test data and compare with real test data to calculate the errors
- Predict 3 years into the future to forecast the future values, and calculate ROI on the corecasted values
- Sort the zipcodes by their forecasted ROI to find the top zipcodes

#### Content of this repository
- zillow_data.csv : this is the house sale dataset from Zillow. The data source of this project.
- Project3.ipynb : this is the main technical Jupyter notebook that perform all data science process of this project.
- Presentation.pdf : this is the executive presentation that provide the final conclusion of this project

THANK YOU!
