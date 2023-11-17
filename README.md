# Datathon-5

## Research Questions

- Forecasting: Can we use the sensor data to forecast future activities? For instance, based on the current sensor readings and past activities, could we predict what activity the person is likely to perform next? This would involve using time-series forecasting techniques, such as LSTM
- Activity Recognition: Can we develop a model that can accurately predict the type of activity a person is performing based on their sensor data? 
See what features contribute more to specific activities
- Movement Pattern Analysis: Can we analyze the movement patterns of individuals and use this information to gain insights into their health and fitness levels?
- Anomaly Detection: Can we use the sensor data to detect anomalies or unusual patterns that could indicate a health condition?

## Steps

### Data cleaning
- Create the sequence for each person: move the observations of the same person to adjacent rows
- Decide the sequence size to use
- No feature selection needed
- Check whether there are great jumps in the data/actions
  
### Build an LSTM model
