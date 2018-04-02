# Forecasting

A basic algorithm for *forecasting*, regardless of method:

```
1. Partition the data into two segments, say the first three years of history and the final year of history.
2. Develop an initial forecast model using one of the methods I will discuss
3. Input the three years of historical data into the model and produce a forecast for the fourth year.
4. Compare the forecast values for the fourth year with the actual fourth year sales history and thereby determine how accurate your forecast model is.
5. Make modifications to your model that you believe will improve the forecasts, that is, reduce the forecast errors.
6. Repeat steps 2 through 5 until you can no longer reduce the errors in your forecast.
7. Use your model to produce forecasts of future sales.
```
  * From Introduction to Business Analysis by Matthew Crabtree (University of Waterloo / Ed2Go) 
  
 A **forecast model** is a mathematical model of the values you want to try to determine (forecast).

## Types of Forecasting

* Qualitative
  * Bottom-up
  * Scenarios
  * Delphi
  * Others
* Quantitative
  * Moving average
  * Smoothing methods
  * Trends
  * Seasonal Influence
  * Others
  
### Quantitative Forecasts
#### Moving Averages
**Note:** Error is always calculated as `\[Actual Data\] - \[Forecasted Data\]`.

Use Mean Squared Error (MSE) instead of error values, to measure the effectiveness of your forecast model. Your job is to minimize MSE.
