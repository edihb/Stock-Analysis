# Stock-Analysis
This project analyzes the polynomial and STL trend of a particular stock and creates a simple visualization of the data. </br>
Predictions of the trend are made using prediction techniques such as linear model, ARIMA,
Holt-Winters and Neural Networks in <a href="https://www.r-project.org/"><b>R</b></a>. </br>
Further, the project also estimates which prediction model for the stock is closest to its actual trend.

# Implementation
The input monthly stock value files downloaded from 
<a href="https://finance.yahoo.com/">Yahoo Finance</a> are in the stocks folder. </br>
The input files are csv files with the following fields - </br>
Date, Open, High, Low, Close, Volume, Adj Close </br>
The www folder stores the Bootstrap associated with the app frontend. </br>
<b>server.R</b> and <b>ui.R</b> are the primary files for the project. </br>

# R packages used
<b>forecast -</b></br>
Forecasting Functions for Time Series and Linear Models. </br>
https://cran.r-project.org/web/packages/forecast/index.html </br>
<b>fpp -</b></br>
Forecasting: principles and practice </br>
https://cran.r-project.org/web/packages/fpp/index.html </br>
<b>shiny -</b></br>
To build an interactive webapp straight from R. </br>
https://shiny.rstudio.com/</br>
<b>shinythemes - </b></br>
https://rstudio.github.io/shinythemes/ </br>
