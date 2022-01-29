# Weather web scraping- Time series Model
Scraping /www.timeanddate.com web with bs4 tool in python for London weather of 7 years.

I got two different types of data - Actually they have different date and hours split:
you can find them in "raw data folder".

- Data from script:
<img src="/Pictures/Script.png" width="30">

- cleaned the data with separate months and days and some extra strings like wind units along with their numbers (dataset folder)
- Analyse features :
 
- For 7 years
<img src="/Pictures/SevenYear.png" width="30">
- For one year
<img src="/Pictures/OneYear.png" width="30">

- Test some ML models, RNN and LSTM models on dataset.
- 
- Result of RNN:
<img src="/Pictures/RNN_result.png" width="20">

- Result of LSTM:
<img src="/Pictures/LSTM_result.png" width="20">
