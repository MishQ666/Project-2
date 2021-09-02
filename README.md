# Alpha Analysts
#### Authored by: [Jenny](https://github.com/jennyntd), [Michelle](https://github.com/MishQ666), [Scott](https://github.com/Bomegolf), and [Thapa](https://github.com/TribThapa)


## Summary 
Our project is aiming to predict the direction of a list of US top performing stocks. 

![alpha analysts](https://techcrunch.com/wp-content/uploads/2019/06/GettyImages-1051659174.jpg?w=730&crop=1)

*General Advice Warning*
*Information published on this website has been prepared for general information purposes only and not as specific advice to any particular person. Any advice contained in this document is General Advice and does not take into account any person’s particular investment objectives, financial situation and particular needs.*

*Before making an investment decision based on this advice you should consider, with or without the assistance of a qualified adviser, whether it is appropriate to your particular investment needs, objectives and financial circumstances.  Past performance of financial products is no assurance of future performance.*

*Due to time limitation, we are focusing on Amazon only for demonstration purpose.*


## Project description

Our project aimed to determine BUY-SELL signals for top performing US stocks using MACD indicators and TimeSeries analysis. 

- TimeSeries analysis was used to determine stock price 5-days moving forward
- MACD indicators were used to determine bullish or bearish movement in the market to reflect stock price strengthening or weakening 

[TradeSignal](https://github.com/MishQ666/ProjectTwo-Alpha-Analysts/blob/main/Image/AMZN_TradeSignal.png)


Besides, we also used Classification and Regression machine learning models to train and predict stock prices:

Regression models:
- Regression
- Linear Regression
- Random Forest
- Extra trees
- Lasso Regression
- Ridge Regression
- Stochastic Gradient Design
 
Classification models:
- Classification
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Ada Boost Classifier
- XGB Forest Classifier

Insert summary chart here
In summary, Ridge Regression and Linear Regression models are a relatively better prediction model, with Linear Regression having a slightly lower Root Mean Squared Error, being the best performing model among all regression models above.

 
Insert summary chart here
According to the chart above, the results are the same thus provided limited insights
 TIME SERIES
Insert chart
We used ARIMA model indicating that it is a good fit for stock price prediction.
Algo trading/ backdatingResources/ or Packages we used
Insert chars
Bonus: Our back-testing results indicated a return of $XXX if investors practice a hold strategy when compared to actively trading according to the MACD signals.

## [Presentation](https://github.com/MishQ666/Project_2/tree/main/Presentation)


## Prediction and Conclustions

Our prediction 

## Sources
- [Google Colab](https://drive.google.com/drive/folders/1abuvNk-AlsIswHqVwza9GbKKlGb1UYDL)
- [ScikitLearn](https://scikit-learn.org/stable/)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)
- [Yfinance](https://pypi.org/project/yfinance/)
- [Vectorbt](https://vectorbt.dev/)
- [Quantstats](https://www.youtube.com/watch?v=gsS3JxPXXvg)











