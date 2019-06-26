# StockReport--Dashboard

![x](stockReport.png)


# Background

Stock Time Series HTML Report

we will complete our financial time series project by building an HTML report page for our visualizations.


# Goals

* Use Bootstrap to build a financial report HTML page.

  * This page should include the following:
 

    1. A Plotly time series plot of the stock.

    2. A Table of the 12 month stock data

    3. A company summary panel
    
* The array passed to this function (the function rollingAverage) will the closing price data for the stock.

* Inside the function, loop through the stock closing price array and calculate the average for a sliding window of 30 days.

* Build a table of the monthly stock data using `Plotly.d3`.

