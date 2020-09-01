# Taxi fare prediction
 
 An exploratory analysis was carried out and a model was created to forecast the taxi fares in NY


# [Project :  Taxi fare prediction](https://github.com/bezerraluis/Luis-Paulo-Bezerra/blob/master/Projects/corrida_taxi.ipynb)
 
 ![taxi](https://github.com/bezerraluis/Luis-Paulo-Bezerra/blob/master/images/taxi.jpg)
 
 
 
 # Data fields

ID
key - Unique string identifying each row in both the training and test sets. Comprised of pickup_datetime plus a unique integer, but this doesn't matter, it should just be used as a unique ID field. Required in your submission CSV. Not necessarily needed in the training set, but could be useful to simulate a 'submission file' while doing cross-validation within the training set.

## Features

pickup_datetime - timestamp value indicating when the taxi ride started.

pickup_longitude - float for longitude coordinate of where the taxi ride started.

pickup_latitude - float for latitude coordinate of where the taxi ride started.

dropoff_longitude - float for longitude coordinate of where the taxi ride ended.

dropoff_latitude - float for latitude coordinate of where the taxi ride ended.

passenger_count - integer indicating the number of passengers in the taxi ride.
 

1.The database was extracted from this Kaggle competition: https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/overview. 


2.In this competition the task of predicting the fare amount (including tolls) for a taxi ride in New York, given the places of departure and destination. Although you can obtain a basic estimate based only on the distance between the two points, this will result in an RMSE of 5 to 8, depending on the model used. The challenge is to have better results than these using machine learning techniques.

3. Database with 55 million records, so the first step was to create a sample with 250,000 records to perform the analyzes and create the models.

4. Perform data processing

5.Perform exploratory analysis 

6. Perform creation of new variables

7. baseline creation

8. Perform Cross Validation

9.Tuning hyper parameters

10. Choosing the best model with the optimized parameters
