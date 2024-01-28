# Prediction of Russian ruble (RUB) against US dollar (USD) in June 2022 amid Russian-Ukrainian war

## General information 
***Objective #1: EVALUATION OF THE SIGNIFICANCE OF OIL PRICE IN PREDICTING THE USD/RUB RATE.***

Among many other factors that define the exchange rate of USD/RUB, such as inflation rate, interest rate,, and government debt, we wanted to evaluate the extent to which the oil price affects the USD/RUB rate. 

***Objective #2: PREDICTION OF USD/RUB AVERAGE IN JUNE 2022.***

Using different models, we aimed to predict the average exchange rate of USD/RUB in June 2022 as such prediction is valuable for financial decision-making of individuals and organizations. 

## Methodology
***Step 1: EXPLORATORY  DATA  ANALYSIS*** 

EDA showed that after the devaluation of the ruble followed by  Russia’s first invasion of Ukraine in February 2014, the rate of change of USD/RUB only stabilized in early 2018

***Step 2: SPLITTING DATA TO TRAINING AND TESTING SETS***

Data was split from 12-2003 to 02-2018 and from 03-2018 to 05-2022 for training and testing sets respectively (77/23 ratio.) 

***Step 3:  LINEAR REGRESSION MODEL***

Linear Regression models were built using different combinations of features.

***Step 4:  KERAS DEEP LEARNING MODEL***

Keras Deep Learning models were built using different combinations of features.

## Technologies 
* Jupyter Notebook

## Setup 
The following R packages were used for this project: 

* bs4
* requests
* pandas
* dateutil 
* numpy 
* matplotlib
* sklearn
* keras

## Features 
The following forecasting methods are explored in this project:

* Linear Regression
* Deep Learning 

## Results 
![Comparison between Linear Regression and Deep Learning models built by using different combinations of features.](https://github.com/juldyzmurat/USD-RUB-rate-amid-Russian-Ukrainian-war/blob/main/Results.png?raw=true)

Since confident level of all six models have a very similar range, mean absolute percentage error played a major role in choosing the linear model with only four variables of USD/RUB exchange rate and Oil Price.

Exploration confirms the findings of earlier studies that oil price is a significant factor in forecasting the USD/RUB value due to Russia’s oil-dependent economy (Kim,2018). Using the two currency exchanges (USD/RUB and EUR/RUB) and one (USD/RUB) produces different results as currency included oil price factor. The effect of oil price was also confirmed by feature analysis of linear model. 

The predicted value confirms the trend observed in the previous invasion, which caused a rapid devaluation of the Russian currency, followed by its rapid revaluation - the current state of the ruble. 

Exploratory analysis is also reflected the effect of regulations of Russia as a response to Western sanctions, namely its strict selling of oil in the ruble (McCabe,2022), which resulted in a rapid strengthening of the currency, which is expected to be observed in June. 

## Status 
Project is: complete
![First Place Winners of the National Student Data Corps Data Science Symposium.](https://github.com/juldyzmurat/USD-RUB-rate-amid-Russian-Ukrainian-war/blob/main/first%20place.png?raw=true)

## Contact 

## Acknowledgements 

