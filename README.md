# Complex-Deep-Learning-Architectures-For-Predicting-Stock-Prices
This research explores the underlying mechanisms through which advanced deep learning models augment predictive performance in forecasting S&amp;P 500 stock closing prices.

Therefore, our primary objective is to see empirically the difference in performance of themodels and try to understand the factors contributing to the superior 
efficacy of state-of-the-art models compared to a conventional feed-forward neural network (ANN).

The models considered are Long-Short-Term-Memory (LSTM) and Temporal Fusion Transformer (TFT). The Artificial Neural Network(ANN) is regarded as the baseline due to its comparatively simpler
architecture among deep learning models.

Each model's predictive framework involves forecasting the closingprice of the S&P 500 by utilizing historical closing prices from
previous days.

The analysis considers two specific timeframes: the preceding 5 days and 20 days. This exploration is crucial for comprehending how the predictive performance of each model varies with higher or lower numbers of lagged features. 

The metrics used for evaluating each model are the Mean Absolute Error (MAE), the Root Mean Square Error (RMSE), and the Mean Absolute Percentage Error (MAPE).

The empi rical results of our study highlight:
- Certain models exhibit improved performance with a reducednumber of lagged values, while others demonstrate a
  preference for a higher series of lagged values. We aim to explain this observation by going through the architecture of each model.
- The superior predictive capabilities of advanced deep learning models, LSTM and TFT, in capturing the intricate dynamics
  inherent in stock prices.
