# Train Delay Estimation

## Overview

* All the statistical analysis (EDA, Data Preparation, model) are in the **Solution.ipynb** notebook.
* Additionally you can also refer to "report.html" for the EDA.
* Please find the **RishabPal_solution.csv** file for the test results. 

## Environment
* python == 3.6.8
* Ubuntu 18.04 LTS

## Setup
$ pip install -r requirements.txt

## Evaluation Results (on 10% validation set)

### Random Forest Regressor
* **ArrivalDelay MAE:** 0.451
* **DepartureDelay MAE:** 0.043

* **ArrivalDelay RMSE:** 23.662
* **DepartureDelay RMSE:** 23.107

### LightGBM

* **ArrivalDelay MAE:** 0.109
* **DepartureDelay MAE:** 0.489

* **ArrivalDelay RMSE:** 36.951
* **DepartureDelay RMSE:** 36.348

## Improvements

* Identify mmore Key Performace Indocators (KPIs) and add it to the dataset.
* Data Distribution between train, validation and test set should be kept uniform. 
* Train on a larger dataset. 
* Use time-series analysis.

## Papers
* [Estimating Train Delays in a Large Rail Network Using a Zero Shot Markov Model](https://ep.liu.se/ecp/069/059/ecp19069059.pdf)
* [Predictive Model of Train Delays in a Railway System](https://arxiv.org/pdf/1806.02825.pdf)
