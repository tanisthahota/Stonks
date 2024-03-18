Stonks📈 a Time-Series analysis on stock market
This project is about forecasting the values for the next 9 months of a few stocks in the indian stock market namely - HAL, BDL and ZENTEC.
I did data analysis and understood the data by plotting a few graphs. I then prepocessed the data where i checked for null values and found outliers by doing a box plot for the highs and lows of the selected stocks. I found outliers for 2 of the stocks and did outlier treatment by replacing all outliers by mean values of the column. I also split the data in the ratio of 70-30 where 70% was my training dataset and 30% was my testing dataset.
The next step was hypothesis testing to check if my data was stationary or seasonal. I performed ADF , KPSS and ANOVA testing. I didnt perfomr z test cuz my data set didnt have a large range , didnt do t testing as my dataset was more than 30 values and khi^2 is for qualitative data and my dataset didnt have that.
Training forecasting models :
ARIMA, 
SARIMA,
PROPHET,
HOLT WINTERS,
LSTM
