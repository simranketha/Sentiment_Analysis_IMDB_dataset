# Sentiment_Analysis_IMDB_dataset

IMDB dataset is used in this work.
## IMDB Dataset description
IMDB is the Large Movie Review Dataset. 
* The dataset consists of 50,000 reviews from IMDB on the condition there are no more than 30 reviews per movie. 
* The numbers of positive and negative reviews are equal.
* Negative reviews have scores less or equal than 4 out of 10 while a positive review have score greater or equal than 7 out of 10.
* Neutral reviews are not included. 
More information on the dataset can be found: http://ai.stanford.edu/~amaas/data/sentiment/

## Sentiment _Analysis_Logistic_Regression
* BOW, TF-IDF are used for feature extraction.
* Logistic regression classifier is used for classification.


## Sentiment _Analysis_IMDB_Dataset
* Sentiment_Analysis using deep learning.
* Sentiment Analysis is done on IMDB Dataset that comes bundled with Keras. 
* It consists of 25,000 training samples (of which 20% are taken for validation) and 25,000 test samples. All words in the dataset are pre-tokenized. Self-trained word embeddings are used (the Keras Embedding layer).
*Conv1D,Dropout,Fattern,Dropout are used.
