# Weather web Scraping - Time series Model
Scraping www.timeanddate.com web with bs4 tool in python for London weather of 7 years.
"YearLondon_Weather" is cleand data which I used it for models has 10222 records.

I got two different types of data - Actually they have different date and hours split (raw data):

- cleaned the data with separate months and days and some extra strings like wind units along with their numbers (dataset folder)
<img src="/Pictures/Script.png" width="1200">

Analyse features (process_data) :
- Temp, Barometer and Humidity changes in 7 years: 
<img src="/Pictures/SevenYear.png" width="1200">

Test some ML models, RNN and LSTM models on dataset that you can see some results here.
- Result of RNN:
<img src="/Pictures/RNN_result.png" width="500">

- Result of LSTM:
<img src="/Pictures/LSTM_result.png" width="250">
