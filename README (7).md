
## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://katherineoelsner.com/)
[![linkedin](https://www.linkedin.com/in/aditya-rekhate-0b320314b)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/)


## Yes-Bank-Stock-Closing-Price-Prediction
#ML regression project

A stock (also known as equity) is a security that represents the ownership of a fraction of a corporation. This entitles the owner of the stock to a proportion of the corporation's assets and profits equal to how much stock they own. Units of stock are called "shares." The value of shares depends on the investors, whether more people are buying the stock or selling it, follows the simple supply – demand rule.

So my project was to apply different regression models on the given data to predict the closing price of the stock, then compare all the models to figure out the best one for this job.

I started off with data overview, just to understand what’s in the dataset and plan out the steps to get the final result.

Next step was to perform EDA, do the required feature engineering steps and carry out univariate/bivariate analysis.

In the next step, I split the data into train and test data set and ran the following regression models-

1.Linear regression
2.Lasso regression
3.Ridge regression
4.Elastic net regression

I also saved all the evaluation metrics in a data frame.

In the end, I compared all the metrics and came to the following conclusions-

1.Using data visualization on our target variable, we can clearly see the impact of 2018 fraud case involving Rana Kapoor as the stock prices decline dramatically during that period.

2.After loading the dataset, we found that there are no null values in our dataset nor any duplicate data.

3.There are some outliers in our features however this being a very small dataset, dropping those instances will lead to loss of information.

4.We found that the distribution of all our variables is positively skewed. so we performed log transformation on them.

5.There is a high correlation between the dependent and independent variables. This is a signal that our dependent variable is highly dependent on our features and can be predicted accurately from them.

6.We found that there is a rather high correlation between our independent variables. This multicollinearity is however unavoidable here as the dataset is very small.

7.We implemented several models on our dataset in order to be able to predict the closing price and found that all our models are performing remarkably well and Elastic Net regressor is the best performing model with A R2 score value of 0.9938 and scores well on all evaluation metrics.
