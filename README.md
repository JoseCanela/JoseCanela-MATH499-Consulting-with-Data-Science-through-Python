# Data Science Projects/Assignments - Topics range from finance to object recognition

## 1. "SPY vs NAESX"
### Official Project Title: *A Simple Forecast of a SPY-&-NAESX-Comprised Portfolio's Monthly Mean Return*
* Built a portfolio out of SPY and NAESX data and developed a **linear regression** model to predict monthly portfolio returns using lagged, previous returns. 
* This effort consisted of utilizing given SPY and NAESX, **data wrangling** (employing **Pandas and NumPy**), **statistical model development** (using **Scikit-Learn**), *backtesting*, and *model evaluation* using RMSE and R^2.

## 2. "Excess Market Return prediction"
### Official Project Title: *Forecasting Excess Market Returns for Portfolio Building*
* Developed a **rolling linear regression** model to predict excess market returns and calculate portfolio returns. This strategy was compared with a baseline model that puts 100% into the market to see which strategy performs better (with respect to the mean and standard deviation of their resulting excess market returns).
* This effort consisted of utilizing given 2017 stock data (primarily focusing on **E/P ratio**, **term spread**, **default spread**, **net issuance**, **market return**, and **risk-free return**), **data wrangling** (employing **Pandas and NumPy**), and **statistical model development** (using **Scikit-Learn**).

## 3. "Multi-Indexing ETF Time Series Data"
### Official Project Title: *Employing Basic Strategies for Building ETF Portfolios*
* Built ETF portfolios based on mean returns of every stock in a given 2018 ETF dataset.
* This project involved **exploratory data analysis** (**EDA**), **multi-indexing ETF data by permanent number**, the
unique identifier of a given ETF, **and by month** (employing **Pandas and NumPy**), **breaking up stocks into quintiles based on their mean returns**, and **building a “momentum” style portfolio** where, every day, one buys some weight of the highest quintile of ETFs and shorts some weight of the lowest quintile of ETFs.

## 4. "Web Scraping Stock Data"
### Official Project Title: *Yahoo Finance Web Scraper*
* Developed a web scraper that scrapes the summary statistics (from “*Previous Close*” to “*1y Target Est*”) of any given stock or list of stocks from the Yahoo Finance web page and cleanly displays these statistics in a data table.
* This project was completed using **Python**. It consisted of data wrangling (utilizing **Pandas**, **NumPy**, and **datetime**) and **web scraping the Yahoo Finance page** (using **Beautiful Soup** and **requests**).

## NOTES:
* All of the projects above have exercise prompts and data files so that the reader can follow along and see the steps that I took to complete each project.
* For this class (*MATH 499 - Consulting with Data Science through Python*), I also worked on two major team projects:
  1. [***"Developing a More Concise Life Insurance Application for Risk Classification"***](https://github.com/JoseCanela/Life-Insurance-Risk)
  2. [***"U.S. Traffic Sign Detection Using Convolutional Neural Networks – YOLOv3".***](https://github.com/JoseCanela/Traffic-Sign-Detection)
* Unfortunately, at the time, my group members and I were not commiting our work on GitHub that much as we were completing our project sprints. Hence, these projects will be posted in their completed form. **These two projects will have their own repositories dedicated to them so that they are easy to access**:
  1. [***Life-Insurance-Risk***](https://github.com/JoseCanela/Life-Insurance-Risk)
  2. [***Traffic-Sign-Detection***](https://github.com/JoseCanela/Traffic-Sign-Detection)
