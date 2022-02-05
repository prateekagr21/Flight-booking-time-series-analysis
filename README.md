# Flight-booking-time-series-analysis!! 
## Time Series analysis of Air passangers using FbProphet

_`Prophet is a forecasting procedure implemented in R and Python. It is fast and provides completely automated forecasts that can
be tuned by hand by data scientists and analysts.`_

![plane1](https://user-images.githubusercontent.com/73397927/151483176-32c7185e-f4df-4964-9d80-720d1c94390f.jpg)

_As air travel is considered a relevant area of action to mitigate climate change, it is important to know its determinants. <br> The present study examines socio-demographic, spatial and attitudinal predictors of air travel for private purposes._


_The analyses are based on the Swiss Environmental Survey 2007 and a subsequent computation of the respondents' environmental impact, as well as spatial data._

_A lognormal hurdle model indicates that persons with higher environmental concern are less likely to travel by air and if they still do, they travel less. While political orientations do not affect whether a person travels by air, the results indicate that among those who do fly, respondents voting for the Green Party cause lower emissions than those opting for other left or center parties. <br><br> Furthermore, higher incomes are associated with more air travel whereas living with children is associated with less air travel._


_Airport access is related to air travel in the sense that living closer to airports, in particular to large ones, is correlated to more air travel. The result is robust to alterations of the accessibility measure and also upholds when population density is controlled for._

![plane2](https://user-images.githubusercontent.com/73397927/151483201-1d25f92a-ee9a-46c7-be23-9a9ceb61995e.jpg)

## For Solving this Usecase, What I have done is :
- Collected the data and organized it to form a meaningful dataset.
- Checked for null values and took care of it.
- Observed the data to form meaningful insights!
<br><br>
- Did Exploratory Data Analysis on the dataset.
- Used correlations to form a heatmap.
- Visualizations were made by using Matplotlib and Seaborn Libraries..!!


## Did Data Pre-Processing :
To fit and transform Numerical and Categorical Column values.
- FbProphet's visualizations were used to make graphs and intutive visuals


## And then I made my model for the Prediction :
- Imported FbProphet.
- Fitted the model.


#### _And then, Created and added 365 days to the data df !_


## Trained my Model using :

![plane3](https://user-images.githubusercontent.com/73397927/151746536-6a0e57d1-0af6-465b-996e-486fec1fa886.jpg)

## _FbProphet_
- Fitted the model.
- predicted the test scores and checked the same.
- Plotted the prediction.

#### _Also, plotted the projections of yearly trend._

## Did Cross Validation
Measuring the Forecast Error by Comparing the Predicted values with Actual values!

## Plotted the Performance matrix of :
- Mean Squared Error(MSE)
- Root Mean Squared Error(RMSE)
- Mean Absolute Error(MAE)
- Mean Absolute Percentage Error(MAPE)
- coverage = yhat_upper - yhat_lower

![plane4](https://user-images.githubusercontent.com/73397927/152623700-0d998d75-5228-4b84-b5b1-973cec4166e9.jpg)

## _And for the conclusion -_
#### _From the above trained Model, It can be seen that the FbProphet model performed better and with help of that, we are able to figure out a pattern in the Time Series projection._
#### <br> _The prediction we see through the graph are quite natural, what can i say, using this tool for time series analysis was a fair choice after all !_

---
