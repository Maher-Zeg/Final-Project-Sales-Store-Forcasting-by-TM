![68747470733a2f2f6269742e6c792f32566e58577232](https://user-images.githubusercontent.com/94024100/153522701-d818c003-7225-43df-b118-10f80053b96f.png)



# Final-Project-Sales-Store-Forcasting-by-TM

# Store Sales - Time Series Forecasting

[Maher Zeghida]

[Data Analytics, Paris, 11.02.2022]





## Project Description

This project is about time series forcasting for store sales. The data comes from an Ecuador company as known as Corporación Favorita and it is a large grocery retailer. Also, the company operates in other countries in South America.

There are 54 stores and 33 prodcut families in the data. The time serie starts from 01-01-2013 and finishes in 15-08-2017.




## Work Process

There are 6 data that we will study on them step by step.

Train
Test
Store
Transactions
Holidays and Events
Daily Oil Price

#### File Descriptions and Data Field Information
##### train.csv
The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
store_nbr identifies the store at which the products are sold.
family identifies the type of product sold.
sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

##### test.csv
The test data, having the same features as the training data. You will predict the target sales for the dates in this file.
The dates in the test data are for the 15 days after the last date in the training data.
sample_submission.csv
A sample submission file in the correct format.

##### stores.csv
Store metadata, including city, state, type, and cluster.
cluster is a grouping of similar stores.

##### oil.csv
Daily oil price. Includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and it's economical health is highly vulnerable to shocks in oil prices.)

##### holidays_events.csv
Holidays and Events, with metadata
A holiday that is transferred officially falls on that calendar day, but was moved to another date by the government. A transferred day is more like a normal day than a holiday. To find the day that it was actually celebrated, look for the corresponding row where type is Transfer. For example, the holiday Independencia de Guayaquil was transferred from 2012-10-09 to 2012-10-12, which means it was celebrated on 2012-10-12. Days that are type Bridge are extra days that are added to a holiday (e.g., to extend the break across a long weekend). These are frequently made up by the type Work Day which is a day not normally scheduled for work (e.g., Saturday) that is meant to payback the Bridge.

##### Additional holidays are days added a regular calendar holiday, for example, as typically happens around Christmas (making Christmas Eve a holiday).
Additional Notes
Wages in the public sector are paid every two weeks on the 15 th and on the last day of the month. Supermarket sales could be affected by this.
A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake.

