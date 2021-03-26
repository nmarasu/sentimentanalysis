# Multiclass Sentiment analysis using Reddit WallStreetBets Posts dataset

I used to dataset Reddit WallStreetBets Posts from https://www.kaggle.com/gpreda/reddit-wallstreetsbets-posts for multiclass sentiment analysis. This original dataset do not have any sentiment labels. It has a body and text columns. In this exercise considered only the body column and labeled using NLTK sentiment analyzer as POSITIVE, NEUTRAL, and NEGATIVE. Then, practiced using following models. Also provided each models test dataset accuracy and found that BERT model performed better than 

1. LSTM model - 90% accuracy 
2. BiLSTM - 87% 
3. BiLSTM with FastText embedding - 92%  
4. BiLSTM with Glove embedding - 91.5% 
5. BERT - 94% accuracy 
6. BiLSTM with Glove embedding & attention layer - 92%.

