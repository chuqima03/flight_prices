# flight_prices
URL/location for downloading the data: https://www.kaggle.com/datasets/dilwong/flightprices

This dataset includes the record of every ticket purchase from Expedia during 2022-04-16 to 2022-10-05. It has 27 columns in total including information such as flight date, starting airport, destination airport, travel duration, whether it is a basic economy and refundable ticket, price of the ticket, seats remaining, total travel distance, etc. The data comes in three file formats: "itineraries.7z" contains a .csv file, "itineraries_gzip.parquet" is a gzip-compressed Apache Parquet file, and "itineraries_snappy.parquet" is a snappy-compressed Apache Parquet file. These three files contain the same data. With this information, I am going to build a machine learning model to make predictions on the price of flights using the dataset above. By analyzing the dataset, I want to predict if the flight price is expensive or not (higher than $400). To be specific, how price is affected by time, distance, starting and destination airports or other factors. Since I am going to predict whether the price of flights is higher than $400, I believe I can use a logistic regression to help understand the relationship between flight price and other variables. Logistic regression should be simple and easy to interpret, so I will consider it first. However, if the logistic regression model doesn’t perform well, or if I need to capture some more complex relationship in the dataset, I might also consider other machine learning models.
