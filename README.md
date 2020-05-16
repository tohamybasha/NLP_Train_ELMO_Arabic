# NLP_Train_ELMO_Arabic
A trial to train ELMO model by allennlp on Arabic tweets.
# Task
Classify arabic tweets to the right country out of 27 classes ( countries ).
# Dataset
Data from NADI shared task for arabic nlp 2020. 

# Preprocessing
Cleaned each tweets by removing emojis, english letters, links, hashtags etc..

# Preparing files
Prepared training data as files and vocab file of the whole data.

# ELMO Model
Cloned the repo of AllenNLP : https://github.com/allenai/bilm-tf
editted the options file of it with our vocabs count, then started working on the arabic dataset after cleaning.
Trained on 700k arabic tweets.

# Classification 
Used normal logistic regression to classify the test data.

# Results 
The results wasn't that good.
