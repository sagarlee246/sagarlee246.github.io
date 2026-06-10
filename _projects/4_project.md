---
layout: page
title: Hidden Markov models for predicting stock market returns
description: A stock-prediction project that uses a Gaussian hidden Markov model on Novo Nordisk returns.
img: /assets/img/HMMStocks.jpg
importance: 3
category: Data Science
pdf: /assets/pdf/Hidden_Markov_models_for_predicting_stock_market_returns.pdf
---

I used a Gaussian hidden Markov model to predict Novo Nordisk stock returns from log returns, volatility, and momentum. Three training strategies were compared: training on NVO itself, on the S&P 500, and on a set of comparable pharmaceutical companies.

The best hyperparameters were found with Optuna, and the final model used 7 hidden states with a 30-day rolling window. All three training setups achieved low magnitude error, with the S&P 500-trained model performing slightly best on the combined metric. Directional accuracy stayed below 50%, which means the model was much better at tracking price level than predicting the next move.

As a proof of concept, I also tested a simple buy/sell strategy based on the predictions. It reduced some losses, but the Markov assumption made long-horizon forecasts unstable, so the model is better suited as one component in a broader forecasting pipeline.

[Read the full report]({{ page.pdf | relative_url | uri_escape }})
