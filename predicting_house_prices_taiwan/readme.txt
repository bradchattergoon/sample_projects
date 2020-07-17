This project was the midterm for the Statistical Learning course offered by the Harvard Extension School. The aim was to develop and test a model for predicting housing prices in the form of price per unit area with data from a number of houses sold in the New Taipei City area of Taiwan.

The variables in the data set are:

No=the index of the record
X1=the transaction date (for example, 2013.250=2013 March, 2013.500=2013 June, etc.) 
X2=the house age (unit: year) 
X3=the distance to the nearest MRT station (unit: meter) 
X4=the number of convenience stores in the living circle on foot (integer) 
X5=the geographic coordinate, latitude. (unit: degree) 
X6=the geographic coordinate, longitude. (unit: degree) 
Y= house price of unit area (10000 New Taiwan Dollar/Ping, where Ping is a local unit, 1 Ping = 3.3 meter squared) 

The final model consisted of the following:

Intercept
House Age
Distance to MRT station
Number of Nearby Convenience Stores
An indicator variable for location with three levels: Urban1, Urban2, and Rural

The model adjusted R^2 is 0.7657.

Original Dataset can be found at: https://archive.ics.uci.edu/ml/datasets/Real+estate+valuation+data+set 