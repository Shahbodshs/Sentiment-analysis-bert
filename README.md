# Sentiment analysis with bert (fine-tuned).
I have already implemented a sentiment analysis model with BLSTM architecture here: [BLSTM-sentiment](https://github.com/Shahbodshs/Sentiment-Analysis).
But as i promised i wanted to implement a model with the same dataset using a transformer model, so i decided to work with bert the cased version of it. 
## Explanations about the code: 
1. I have made the dataset alot smaller for the sake of traning time as it usually takes a long time. (dropped from 1.6 million to 100k) also since we are trying to fine-tune the model, it really isnt 
that necessary to use a large dataset. 
2.  The i used Cased version of bert model with classification head, since we have only two labels i put the num_labels value to 0.
## Dataset
You can have access to the dataset here : [sentiment.140](https://www.kaggle.com/datasets/kazanova/sentiment140)
## Code file
You can have access to the code file in the code branch. 

## Kaggle source: 
[Kaggle](https://www.kaggle.com/code/shahbodsobhkhiz/sentiment-analysis-with-bert)

# UPDATE:
I have made a new code file, which i trained a new model using bert and a new dataset from a competition in kaggle: [Bag or words bag of popcorn](https://www.kaggle.com/competitions/word2vec-nlp-tutorial).
The competition is about movie review sentiment analysis. 
i have reached 94 percent accuracy, the problem with the code is, it has a high validation loss compared to the trainig loss, which should be made better. 
In the next update, i will try to make a better model. 
But this, is overall a lot better than the previous model. 
