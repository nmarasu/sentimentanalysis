# Multiclass Sentiment analysis using Reddit WallStreetBets Posts dataset - Pytorch

I used the dataset Reddit WallStreetBets Posts from https://www.kaggle.com/gpreda/reddit-wallstreetsbets-posts for multiclass sentiment analysis. This original dataset do not have any sentiment labels. It has a body and text columns. In this exercise considered only the body column and labeled using NLTK sentiment analyzer as POSITIVE, NEUTRAL, and NEGATIVE. Then, practiced using following models. Also provided each models test dataset accuracy and found that BERT model performed better than the other models.

1. BiLSTM - 87% 
2. BiLSTM with FastText embedding - 92%  
3. BiLSTM with Glove embedding - 91.5% 
4. BERT - 94% accuracy 
5. BiLSTM with Glove embedding & attention layer - 92%.

