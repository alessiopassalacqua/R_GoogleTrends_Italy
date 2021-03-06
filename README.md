# R Shiny + flexdashboard with code

## Motivation

This demo app demonstrates how it is possible to combine the best of modern R &#x1F4E6; packages to create interactive web applications at zero cost and without HTML, CSS, or JavaScript knowledge.

## The App: Google Trends Italy/US

Based on search term, the app takes data from google trends and shows results about Italy or US depending on the user selection.

These are the two main pages:

**Dashboard**

* Trends over the time and forecasting
* Interest by city (top ten)
* Regional Interest

**Download Forecast Data**


## Link

* &#x1F431; [github repository](https://github.com/alessiopassalacqua/R_GoogleTrends_Italy)
* &#x2728; [live app](https://alessiopassalacqua.shinyapps.io/R_gtrends_italy/)


## History Version

1. Google trends Italy
2. Added google trends US
3. Added Download Forecast Data


## R Packages

* &#x2728; `{Shiny}` provides an elegant and powerful web framework for building web applications using R.


* &#x1F4CA; `{highcharter}` is a rich R interface to the popular Highcharts JavaScript graphics library.

* &#x1F4BB; `{flexdashboard}`  helps construct flexible, attractive, interactive dashboards.

* 	&#x1F527; `{dplyr}`  contains a set of functions (or “verbs”) that perform common data manipulation operations such as filtering for rows, selecting specific columns, re-ordering rows, adding new columns and summarizing data.

* &#x1F52E; `{forecast}`  contains function for 
automatic forecasting determining
an appropriate time series model, estimate the parameters and compute the forecasts.

* &#x1F4D1; `{stringr}` contains functions for manipulating strings in R.

* &#x1F4C5; `{lubridate}`  facilitates working with dates and times.

* &#x1F4C8; `{gtrendsR}` provides an interface for retrieving and displaying Google Trends information.

* &#x1F4DD; `{DT}` provides a R interface to the JavaScript library DataTables. R data objects (matrices or data frames) can be displayed as tables on HTML pages, and DataTables provides filtering, pagination, sorting, and many other features in the tables.

## Numbers

* &#x1F4C4; 1 file
* &#x1F55A; 1 day of work (starting from tutorials of one of my courses)
* &#x270D; 200 lines of code
* &#x1F6BF; 30 %>% pipe
* &#x1F939; 100% fun



## Reference

* [Sales Report with Highcharter](https://beta.rstudioconnect.com/jjallaire/htmlwidgets-highcharter/htmlwidgets-highcharter.html)
* [Highcharter Italy Map](https://rpubs.com/jbkunst/Highcharter-Italy-Map)
* [Using Action Buttons](https://shiny.rstudio.com/articles/action-buttons.html)
* [Forecasting: Principles and Practice](https://otexts.com/fpp2/)
* [Pimp my RMD: a few tips for R Markdown](https://holtzy.github.io/Pimp-my-rmd/)