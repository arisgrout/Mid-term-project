# Flight Delay Prediction
**Contributors:** [Aris Grout](https://github.com/arisgrout) & [Wonho Choi](https://github.com/Wonhochoi123)

## Objective
Create a supervised machine-learning model for predicting US flight delays and find KPIs that are predictive of flight delays.

**Why?**\
* In 2019, flight delays costed the aviation industry $33 billion in the USA. This cost has trended upwards the last few years (from 2016-2019; +12.24%, +13.53%, +9.27%).
* By understanding the KPIs impacting flight-delay times, aviation companies can create supportive procedures to mitigate their flight delays and delay-associated costs.

## Approach
1. Exploratory data analysis (EDA) - understand the data (SQL/pandas).
2. Clean data - remove/mitigate errors, outliers, biases (numpy/pandas/stats).
3. Feature engineering & selection - create composite/decomposed meta-data and select features most likely to affect flight-time.
4. Model selection - select suitable ML models for predicting flight-delays.
5. Training & tuning - test, tweak and design the final ML model capable of making accurate predictions with new data.

## TODO
6. Summarize conclusions in this readme.
7. File-tree to explain relationship between scripts.

## Presentation
[Google Slides](https://docs.google.com/presentation/d/1AqPuf7cTp_LwFIrEDJatkQh8GtNO-lg3sR-FjtBLZY8/edit?usp=sharing)

## Data
flights - the departure and arrival information about flights in the USA 2018-2019.\
fuel_comsumption - the fuel comsumption of different airlines for years 2015-2019 aggregated per month.\
passengers - the passenger totals on different routes for years 2015-2019 aggregated per month.

**Evaluation**\
flights_test - the departure and arrival information for flights in the USA in January 2020. This table is used for final evaluation.
* Predicting delays on flights for the first 7 days of 2020 (1st of January - 7th of January).
