# Weather web Scraping - Time series Model
Scraping www.timeanddate.com web with bs4 tool in python for London weather of 7 years.

I got two different types of data - Actually they have different date and hours split:

- Data from script (raw data):
<img src="/Pictures/Script.png" width="1200">

- cleaned the data with separate months and days and some extra strings like wind units along with their numbers (dataset folder)
- 
Analyse features (process_data) :
- Temp, Barometer and Humidity changes in 7 years: 
<img src="/Pictures/SevenYear.png" width="1200">

Test some ML models, RNN and LSTM models on dataset that you can see some their result here.
- Result of RNN:
<img src="/Pictures/RNN_result.png" width="500">

- Result of LSTM:
<img src="/Pictures/LSTM_result.png" width="250">
