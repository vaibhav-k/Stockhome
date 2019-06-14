# Stockhome - CS50 Final Project

Hello respected staff! In this document I will be presenting you my final project for this course. In this project, I have tried to make a machine learning model to predict future trends in a share given its past closing prices. To show my code works, I have analysed the future of Tata Global Beverages. It is a company listed on NSE and I got the data from www.quandl.com. What is interesting in this dataset is that a neural network is able to predict the future quite accurately as compared to the other two. I have made a website with which you can sign up to recieve future data analyses on the email ID you provide when you sign up.

### Website

To send people the data analyses,  I have made a website which has a form. The form has just 3 fields: name, email ID and comments. When the user clicks the submit button, it sends an email to me with the details the user enteres in the form. The website was made using HTML.

### Moving Average

This was the first method I tried to analyse and predict future share prices of the company mentioned beforehand. Averages are something we all use nearly daily in our lives. This is a very simple machine learning technique to find future prices and this mthod performs the worst in comparison to the other 2.

### ARIMA

The full form of ARIMA is "AutoRegressive Integrated Moving Average". This method uses 3 parameters p, q and r. Since that will take a lot of time, I have used autoARIMA which sets these parameters on its own. ARIMA performs better than moving averages but worse than LSTM.

### LSTM

Its full form is "Long Short Term Memory". It is an architecture that is part of neural networks and not just machine learning. This performs the best as compared to the other 2.

#### Made by: Vaibhav Kulshrestha