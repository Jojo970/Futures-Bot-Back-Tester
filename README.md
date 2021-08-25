# Futures-Bot-Back-Tester

### Basic Description
This set of code was what I used initially to test the strategy used in the Rascal PJ bot. The code can be reused by configuring some parameters for trading or by changing the trading pair. 


### How To Use

1. Copy and paste or download the backtester.ipynb file.

2. Import a csv file into the code. Its very important that the csv file contains the indicator information that you want to use.

3. Input the indicator settings that you want to use, they are intentionally left blank in the code for your use. Ex.
```
 if : # put strategy parameters here
            date_of_trade.append(date)
```

Others have indicator 1 and indicator 2 in the spots where the indicators should go. Ex.
```
if indicator_1 and indicator_2 and in_long_position == False and in_short_position == False and date == signals[n]:
```

4. After inputting the parameters, run all cell blocks and in the end, you will be left with an excel sheet detailing your strategy's results.

