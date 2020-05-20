Predictions / Forecasts for validations of electricity time series for hydropower stations
## Prediction files
Prediction files are formated as CSV
Columns in the files are
- date and time (anonymous column, i.e. index in a Pandas [dataframe](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)) on the format %Y-%m-%d %H:%M:%S according to Python's [datetime](https://docs.python.org/3.6/library/datetime.html#strftime-strptime-behavior) 
- gridinput measured in MWh
- kairosgen measured in MWh
- hour of a sample, as an integer [0-23]
- keras prediction in MWh