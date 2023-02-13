# Working-with-SparkSQL

Objective: Analysing IoT Data with Spark Sql

The objective of this case study is to analyse sensor data, which is presented in JSON format, using Spark SQL. 


Dataset (iot_devices.json): The dataset has the following attributes

Device ID
Device Name
IP Address
Cca2 – country code
Cca3 – country name
Cn – Full name of country
Latitude
Longitude
Scale
Temperature
Humidity
Battery Level
CO2 level
LCD Status
Timestamp


Task:

Read the data into a Dataframe.
Convert the Dataframe into a temporary view called iot.
Count how many devices are there from each country and display the output.
Display all the countries whose carbon dioxide level is more than 1400. Sort the output in descending order.
Select all countries' devices with high-levels of C02 and group by cca3 and order by device_ids (Hint: For high CO2 level, the LCD status will be RED).
find out all devices in countries whose batteries need replacements.
