# Three-forecast-types-in-Python
Three one-step forecast types using actuals average previous 3 days (DD), actuals average 10 days like previous month (MM) and full 1354 actuals history in ARIMA.

Additionally to provide 3 forecast types for comsuption of 1 specific product in 6 locations (columns), this code analize history hits on approximation 
per location (between -3 to +3 units deviation).

To ilustrate aproximations: Location 1 (Column 1) shows that once a previous month forecast value (10 previous days 
of comsuption) is given, planner should consider to add +1 on given value to reach best approximation with 23%:

-3 units of deviation from monthly forecast in actuals history has been hit on 8%

-2 units of deviation from monthly forecast in actuals history has been hit on 12%

-1 units of deviation from monthly forecast in actual history has been hit on 14%

-0 units of deviation from monthly forecast in actual history has been hit on 15%

+1 units of deviation from monthly forecast in actual history has been hit on 23%

+2 units of deviation from monthly forecast in actual history has been hit on 13%

+3 units of deviation from monthly forecast in actual history has been hit on 14%

Total % deviation is 99% meaning that only 1% of forecast, monthly forecast value, has been less than -3 units and above than +3 units comparing real consumption and 
forecast value given.
