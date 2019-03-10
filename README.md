# Kaggle_NYC_Taxi_Fare
Introduction:
            This is a simple DNN based model to predict the Taxi Fare in NYC. The dataset used for this is available in Kaggle Competetion.The DNN is implemented using tensorflow. This is a very simple without detailed optimization and feature engineering. The model can be easily trained in any laptop.The code presented here is for interference of the model.
       
# Model Description:
# Input to the Model:
                  These are the features used as input to the DNN Model:
                  1)'pickup_longitude'---> Provided in original Dataset
                  2)'pickup_latitude'--->Provided in original Dataset
                  3)'dropoff_longitude'--->Provided in original Dataset,
                  4)'dropoff_latitude'--->Provided in original Dataset
                  5)'passenger_count'--->Provided in original Dataset
                  6)'pickup_datetimeYear'----> Year of the taxi Ride(e.g:2015,2016 etc). Used fast.ai's add_datepart to extract Year of the                              TaxiFare.
                  7)'pickup_datetimeMonth'----> Year of the taxi Ride(e.g:1,2,3..etc).Used add_datepart function.
                  8)'pickup_datetimeWeek'----> Week of the year (any week from 1-53).Used add_datepart function.
                  9)''pickup_datetimeDay''----> Day of the month(from 1-30).Used add_datepart function.
                  10)'pickup_datetimeDayofweek'--->Day of the week of the Taxi Ride (from 1-7).Used add_datepart function.
                  11)'pickup_datetimeDayofyear'---> Day of the year for taxi ride(from 1-365).Used add_datepart function.
                  12)'pickup_datetimehour'-----> Hour of the day for taxi ride(from 1-24).Used add_datepart function.
                  13)'pickup_datetimeElapsed'--->Time elasped from 1970.
                  14)Herv_Dist: Distance between beginning and end of the ride using Haversine formula.The details of the formula are here:
                  https://en.wikipedia.org/wiki/Haversine_formula
      


