# SP500-index-and-company-returns
This program will download the SP500 stock index returns and its' individual companies returns and import them as CSV file.
This CSV file can be used for further analyzes for example in stock picking by comparing individual company returns to
SP500 index returns for low volatility (beta) stock picking by using regression analysis and its' beta coefficients.

It is noticeable that so far the SP500 company tickers in the code have to be manually updated.


Volatility (beta) portfolio formation principles
************************************************
Haugen and Heins (1992) documented previously in their working paper that the firms with low stock volatility produce 
higher stock returns than companies with high stock volatility. This stock market anomaly is known as Low-volatility anomaly. 
In this strategy the division of companies to low volatility and high volatility stocks is based on publicly available data about 
previous monthly stock return volatility (beta).

Portfolios are being formed of S&P 500 firms based on past monthly stock return volatility (beta) of five years. Companies 
with ranking in the lowest decile in absolute beta ratio were categorized as low volatility stocks and accordingly companies 
with ranking in the highest decile were categorized as high volatility stocks. All the companies were determined to have equal 
portion of the portfolio value.

As the portfolios consist of S&P 500 companies the low volatility portfolio is expected to outperform  S&P 500 index and 
accordingly high volatility portfolio under perform S&P 500 index which is used as benchmark index. The performance of the 
formed portfolios are monitored and updated on a monthly basis and the content of the portfolios are updated after release 
of annual financial statements.
