# Airbnb-Price-Prediction-Madrid

## Basis

I wrote this data analysis and price prediction model in Python on a Jupyter Nodetbook. 

## Questions to be Answered

With this data analysis and price prediction model, the following questions will be answered:

*	Which price can I take for my flat in Madrid? 
*	For which room type can I take which price?
*	Is there a gap in the market for a room_type in any district? 
*	Can flats with at least one review take higher prices?

## The Data I Wanted
To respond those questions the following data was wanted: Airbnb flats in Madrid, average price, if it’s an entire home or just a private room etc., district, neighbourhood, number of reviews, flat size.

## The Data I Got
The data is already available on Kaggle: https://www.kaggle.com/rusiano/madrid-airbnb-data

Here listings.csv was used. Only the flat size could not be found here. It is considered to be negligible.

The data is relatively clean and easy to prepare.
Unfortunately most of the features are not strongly correlated with the price. 

## The Final Model
After checking different Models, the RandomForestRegressor turned out to be the best with a R^2 of 0.6470.


