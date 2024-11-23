1.	Introduction

This dataset is related to crop recommendation based on several environmental factors such as nitrogen (N), phosphorus (P), potassium (K) content in the soil, temperature, humidity, pH, and rainfall. This analysis aims to identify patterns and insights that can assist in recommending the most suitable crops based on these environmental parameters. The ultimate target class is ‘level’ column data of the dataset to improve decision-making in agriculture, helping farmers choose crops that match the conditions of their land and climate.

2. Dataset Description
The dataset consists of 2,200 rows and 8 columns. Each row represents a different environmental scenario with the following features:

•	N: Nitrogen content in the soil (integer).
•	P: Phosphorus content in the soil (integer).
•	K: Potassium content in the soil (integer).
•	Temperature: The average temperature in degrees Celsius (float).
•	Humidity: The average relative humidity in percentage (float).
•	pH: The pH value of the soil (float).
•	Rainfall: The average rainfall in mm (float).
•	Label: The recommended crop type (categorical, object).

The dataset contains numerical values for all features except the label, which is categorical and represents different types of crops.
