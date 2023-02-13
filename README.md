# Working-with-SparkSQL

## Objective: Analysing IoT Data with Spark Sql

The objective of this case study is to analyse sensor data, which is presented in JSON format, using Spark SQL. 


## Dataset (iot_devices.json): The dataset has the following attributes

1. Device ID
2. Device Name
3. IP Address
4. Cca2 – country code
5. Cca3 – country name
6. Cn – Full name of country
7. Latitude
8. Longitude
9. Scale
10. Temperature
11. Humidity
12. Battery Level
13. CO2 level
14. LCD Status
15. Timestamp


## Task:

1. Read the data into a Dataframe.
2. Convert the Dataframe into a temporary view called iot.
3. Count how many devices are there from each country and display the output.
4. Display all the countries whose carbon dioxide level is more than 1400. Sort the output in descending order.
5. Select all countries' devices with high-levels of C02 and group by cca3 and order by device_ids (Hint: For high CO2 level, the LCD status will be RED).
6. find out all devices in countries whose batteries need replacements.
