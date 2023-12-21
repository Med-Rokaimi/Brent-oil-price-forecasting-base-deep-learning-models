# Brent-oil-price-forecasting-base-deep-learning-models
implementing various deep learning networks with Pytorch and Keras using multivariate timeseries data.
#Included models:

1. LSTM / Bi-LSTM
2. GRU/Bi-GRU
3. CNN-LSTM
4. CNN-LSTM-Attention
5. Encoder-Decoder-LSTM
## How to use it:
1. clone the repos.
2. Create your own env and install required packages
```
pip install -r requirements.txt
```
3- run main.py 
```
python main.py [model name]
```
select the network you want from the available model names showed on the main.py (for instance: Bi-LSTM, CNN-LSTM-att, encoder-decoder-LSTM)
4. you can setup selected features (USD, sentiment score, Brent price, you can add as many as columns you want) from arg.py in the config folder. From argg.py you can also tunning models hyperparameters. 
