In this work, we were asked to carry out temperature forecasting based on data provided in the Kaggle competition. This forecasting consist of a set of quantile forecasts corresponding to the following symmetric forecast intervals: 10, 20, 30, 40, 50, 50, 60, 60, 70, 80, 90 and 95% coverages, together with the ‘zero coverage’ quantile 0.5, i.e. the midpoint forecast.
To perform this task, we have been provided with the following data:
- train.csv: Contains 64320 rows of data in which there are 6 columns with anonymous variables, one column with time-stamp variables from 2016-07-01 to 2018-05-01, one column with IDs and the corresponding temperatures.
- test.csv: Contains 5360 rows containing 6 columns with anonymous variables, one column with time-stamp variables from 2018-05-02 to 2018-06-26 and one column with IDs.
- sample_submission.csv: Serves as a template. It has a column with IDs and 21 columns with the predictions of the following quantiles: 0.025,0.05,0.10,0.15,0.20,0.25,0.30,0.35,0.40,0.45,0.50,0.55,0.60,0.65,0.70,0.75,0.80,0.85,0.90,0.95,0.975.
    
In this work we will carry out an EDA by exploring the data to see what conclusions we can draw and we will make a model to forecast the temperatures and to be able to overcome the preset baseline.
