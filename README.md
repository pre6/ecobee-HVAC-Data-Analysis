# How Much Does the Furnace Impact the Gas Bill?


## 1. Visualizing the Data:

The dataset used is from the house thermostat we got in June 29 2022. The data recorded various parameters ever 5 minutes till Dec 18th. These are the first 5 row of the data. 									


Date |	Time |	System Setting |    System Mode 	| Calendar Event |	Program Mode | Cool Set Temp (C) |	Heat Set Temp (C) |Current Temp (C) |Current Humidity (%RH)
|--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |
|	2022-06-29 |	18:05:00 |	off |	heatOff |	NaN |	Home| 25.5 |	20.5 |	25 |	59
|	2022-06-29 |	18:10:00 |	off |	heatOff |	NaN |	Home| 25.5 |	20.5 |	25 |	60
|	2022-06-29 |	18:15:00 |	off |	heatOff |	NaN |	Home| 25.5 |	20.5 |	25.1 |	59
|	2022-06-29 |	18:20:00 |	off |	heatOff |	NaN |	Home| 25.5 |	20.5 |	25.1 |	60
|	2022-06-29 |	18:25:00 |	off |	heatOff |	NaN |	Home| 25.5 |	20.5 |	25.1 |	60

49574 rows × 39 columns



- This is a graph of the average temperature per day in the range:

![image](https://user-images.githubusercontent.com/47339289/218004722-7e02fd14-52b3-4e14-9a14-e078b390c45c.png)


## 2. How much does the furnace cost per day

In the days the furnace runs how much does it cost? Roughly how much does the furnace cost when it turns one once?

This table represents the information in the gas bill.

|Start_Range| End_Range| Amount| Natural_Gas_Supply_Rate (cents/m^3)| M^3 of Gas used|
|--- |--- |--- |--- |--- |
|2022-06-23	|2022-09-01	|109.33	|26.868	  |81|
|2022-09-02	|2022-10-05	|59.51	|27.9027	|57|
|2022-10-06	|2022-11-01	|105.43	|27.9027	|128|
|2022-11-02	|2022-12-02	|164.99	|27.9027	|224|


- The average spent on gas between these 4 ranges is $3.45/day. 

$$ \frac{Total}{days}  $$



- Here is a graph of the price and number of times the furnace is on


## 3. When will I break even with my thermostat??
math math
table 
table
## 4. When will I have to adjust the temperature to save 10%???


math math 
table 
table
