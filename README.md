# 1NTR0_T0_41_081IG4T0RY_N02


Emilis Bruzas - s331428

Tobias Strøm - s331392

Lars Kristian Bårdevik - s331418

RandomForestRegressor

Task: Predicting stock market price for Norwegian airlines using dates as input.

We decided to use regression since we are trying to predict "Close" price, a continuous variable.
Random forest regression combines the results from several multiple decision trees by taking averages based on "groupings" or intervals of target variable values. 
Patterns in our dataset were not reflected well using a linear model, due to frequent spikes and a general deviation from a linear trend.
Random forest looks for the best feature to predict the value of stock price among subsets, which is why it is better at predicting stock market values, as the key features 
affecting change in value might change.
