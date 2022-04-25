# Predict Students' Dropout and Academic Success: Project Overview 
* Created a tool to help predicting Students' Dropout and Academic Success based on students' features (academic path, demographics, and social-economic factors) with an accuracy of 
* Utilized Matplotlib and Seaborn effectively to demonstrate the stock prices fluctuations during the timeframe and what dates each bank stock had the best and worst single-day returns
* Compared the impacts of the COVID pandemic versus the 2007-2009 Great Recession on bank stocks using appropriate plotting and scattering methods


## Code and Resources Used 
**Python Version:** 3.10  
**Packages:** pandas, numpy, matplotlib, seaborn
**Scraper Article:** https://www.bankrate.com/banking/biggest-banks-in-america/ and https://finance.yahoo.com/  

## Web Scraping
Scrape information of 15 banks and their tickers then their stock information from finance.yahoo.com. With each bank, I got the following:
*	High	
*	Low	
*	Open	
*	Close	
*	Volume	
*	Adj Close

## EDA
I looked at the distributions of the data and the value counts for the various categorical variables. Below are a few highlights from the pivot tables. 

![alt text](https://github.com/ahnngo/bank-stocks-affected-by-covid/blob/master/Charts/Banks%20stock%20return.png)
![alt text](https://github.com/ahnngo/bank-stocks-affected-by-covid/blob/master/Charts/Stock%20Return%20over%20Time.png)
![alt text](https://github.com/ahnngo/bank-stocks-affected-by-covid/blob/master/Charts/Stock%20price%20fluctuation.png)
![alt text](https://github.com/ahnngo/bank-stocks-affected-by-covid/blob/master/Charts/Correlation%20of%20Stock%20Prices%20of%20Each%20Bank.png)
![alt text](https://github.com/ahnngo/bank-stocks-affected-by-covid/blob/master/Charts/aximum%20and%20Minimum%20Change%20in%20Close%20Price%20of%20Stocks%20by%20Time.png)

