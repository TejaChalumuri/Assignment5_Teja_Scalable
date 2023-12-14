# Assignment5_Teja_Scalable

For this assignment we have used live stock data to analyse and predict 

We have created and assigned the columns 
Open: float64
High: float64
Low: float64
Close: float64
Volume: float64

## Step 1: Created API for live stock data retrieving 
## step 2: We have selected AAPL stock live data 
## step 3: We have created a function and using the API and stock details have retrived the live data
## step 4: now we have restted the column 
## step 5: Install openjdk-8-jdk and pyspark
## step 6: Imported SparkSession and Streaming Context, pandas, os
## step 7: Now load the data into spark app "StockDataApp"
## step 8: Analysing the data, checking for null values, checking for column schema
## step 9: Import the Linear Regression and VectorAssembler
## step 10: transform the dataset using the vectorAssembler
## Build model usnig the linear regression method 

Now the model is built,

We can print the prediction values 

+------------------+------+
|        prediction| Close|
+------------------+------+
|175.80163947288787|177.56|
|177.19363389106456|177.23|
| 174.6384576562723| 174.0|
| 177.8684217152933|177.79|
| 178.9205136801972|179.07|
|180.67465262662583|181.12|
|178.13462034914633|177.45|
| 179.0553474232227|177.97|
| 176.1377017113623| 176.3|
|178.82684134153766|178.85|
| 183.5405207236848|181.99|
|188.42369902465745|187.87|
|191.32435150354732|191.17|
|192.18447835986126|191.94|
| 193.8128733984012|193.13|
| 195.7094405670107|196.45|
|167.57588598568444|166.89|
|172.86394226526195|173.97|
|173.48550002607305|173.75|
|172.61981999233387|173.44|
+------------------+------+
only showing top 20 rows


## import RegressionEvaluation from pyspark 

## Check for rmse and r2 squared values for evaluation

Root Mean Square Error (RMSE) on test data = 0.7281846575358627
R-squared on test data = 0.9906381979944923

## As we can see that the R-squared value is 99.06% we have no need to hyper tune the model

