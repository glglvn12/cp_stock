# DS_Project

1. LSTM + Sentiment Analysis + Conformal prediction Stock Price Prediction

To enhance the accuracy of LSTM model predictions for stocks, gold, and potential index funds, researchers have incorporated sentiment analysis of daily news headlines using the BERT model, recognizing the significant influence of media on stock markets. To further improve the reliability of these predictions, they have implemented the Conformal Prediction technique, a statistical method that provides prediction intervals with a guaranteed coverage probability. By setting the coverage at 90%, this approach ensures that the true value falls within the predicted interval 90% of the time, offering a robust measure of uncertainty for financial forecasts. This combination of advanced natural language processing and statistical techniques aims to provide more comprehensive and reliable predictions in the volatile world of financial markets.


2. XGBoost + Conformal Prediction Airbnb Price Prediction

To create an Airbnb price prediction model for the US market, we can leverage the power of XGBoost and enhance it with advanced techniques. Using open-source data from Airbnb, we'll train an XGBoost model to predict rental prices. To quantify the uncertainty in our predictions, we'll employ conformal prediction with a conditional coverage target of 90%. While traditional conformal prediction typically uses a single variable for conditioning, we'll innovate by combining coordinate data (latitude and longitude) using K-Nearest Neighbors (KNN) to capture spatial relationships. This approach allows us to account for location-based pricing variations more effectively. After training and evaluating the model, we'll visualize the results on an interactive map, which will not only display the predicted prices but also indicate whether the conformal prediction method successfully achieved the desired conditional coverage across different geographical areas. This visualization will provide valuable insights into the model's performance and highlight any spatial patterns in prediction accuracy.

