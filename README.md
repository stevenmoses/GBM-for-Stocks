# GBM-for-Stocks
Using Geometric Brownian Motion (with drift) to predict future stocks.

## Created by : 

 Group 9 :

- Steven Moses
- Leandro Thiery
- Gilbert Lauren

Undergraduate Computer Engineering student of University of Indonesia

## Created by : 

- Steven Moses

Undergraduate Computer Engineering student of University of Indonesia

## Implementation :

Run [this link](https://colab.research.google.com/drive/18oQ6INx5rmnwU1x5d5O4yYfLGjZyhq0n#scrollTo=2ahq_f0SOiX6) to run the implementation in Google Colab.
  
## Analysis

In the simulation results, we are able to get the predicted value of BCA's stocks in 2019. In the prediction plot, we get an average of 200 simulated paths trendline. The average trendline shows that BCA's stocks in 2019 fluctuates slowly. We count the accuration rate by finding the mean of prediction rate and actual rate, and input them into the formula :

% = (Average Actual Rate - Average Prediction Rate) / Average Actual Rate

From that formula, we get 1.6% error percentage. It shows that this method works for long term. The weakness of this method is it needs a great quantity of past data to make an accurate prediction. This method also used random generator to generate random shocks so it would increase the error percentage.

## More Information : 

For more information about this implementation, you can open [this presentation.](https://drive.google.com/file/d/1y1Id-AWaMF6Kfc4CScse-U9bI9_n1Nzf/view?usp=sharing)

