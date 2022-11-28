# Yes_Bank_Prices_Prediction-Project
# Summary
In this project, exploratory data analysis, visualization, regression models with different types and interesting insights of the data have been performed. This dataset has around 185 observations in it with 5 columns. Fundamental Analysis involves analyzing the company’s future profitability on the basis of its current business environment and financial performance. Technical Analysis, on the other hand, includes reading the charts and using statistical figures to identify the trends in the stock market. The will be on the technical analysis part.

# Objective
We were asked to create a predictive model that could forecast the future stock prices of the bank due to an unprecedented situation like fraud.

# Introduction 
Predicting how the stock market will perform is one of the most difficult things to do. There are so many factors involved in the prediction – physical factors vs. psychological, rational and irrational behavior, etc. All these aspects combine to make share prices volatile and very difficult to predict with a high degree of accuracy. Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations.

# Dataset
This dataset has around 185 observations in it with 5 columns.
Date: The month and the year of the stock prices.
Open: The price at which the stock begins.
High: The highest price at which the stock traded during a period.
Low: The lowest price at which the stock traded during a period.
Close: The price that determines how a stock performed during a period.

# Approach
As a first step, the data as loaded the data and mounted the drive. After mounting the drive, important libraries such as numpy, pandas, seaborn, matplotlib and also all regressions model libraries with their metrics were imported, which are useful for our analysis.

Exploration our data was performed by checking all the necessary parameters like shape, head, tail, information of the columns and their datatypes and description of data like mean, min and max. Exploratory data analysis, normalization, lag creation, preparation of the data and two types of splits were performed.

Finally, the data was fit  using various supervised regression algorithms like Linear Regression, Ridge and Lasso Techniques, Random Forest and Decision Tree Regression. All the performance metrics of these models were compared against each other and the best model was used to predict the stock price.
# Result
Upon using FBProphet and lag columns we found that Linear Regression achieved a R squared score of 98%.  Finally, after going through all the regression models without using lag columns, we achieved an R squared score of 91.% using the Random Forest regressor on the test dataset.

<!-- CONTACT -->
# Contact

If you wish any information on the project feel free to contact me on LinkedIn or by email:

Linkedin: (https://www.linkedin.com/in/suraj-kumar-372048203/)

Email: (surajkumar0892@gmail.com)


<p align="right">(<a href="#top">back to top</a>)</p>
