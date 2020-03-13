# cs175_project
Directories & files:
  application:
    Tweets_Application.ipynb -> applying combined model to three topics, listing example tweets and showing percentage of positive, negative and neutral attitudes.
    tweets.ipynb -> collecting tweets of different topics from Twitter's API
  application_dataset:
    Metoomovement.csv -> tweets related to #MeToo
    Trump.csv -> tweets related to #Trump
    coronavirus.csv -> tweets related to #coronavirus
  evaluation:
    Classification Reports of Classifiers.ipynb -> understanding different models' performance from various perspectives
    Dataset_Size_Threshold.ipynb -> tuning dataset size for running gridsearch on models for tuning parameters
    eli5_eval.ipynb -> use ELI5 library to show feature importances and explain predictions
    manual_test.ipynb -> extract top positive and top negative tweets to examine prediction accuracy
  models:
    Combining Classifiers.ipynb -> combining selected high performance models 
    Gradient_Boost.ipynb -> training, optimizing and showing performance of gradient boost classifier
    Naive Bayes Classifier.ipynb -> training, optimizing and showing performance of naive bayes classifier
    Neural-Network.ipynb -> training, optimizing and showing performance of neural network classifier
    RNN.ipynb -> training, optimizing and showing performance of recurrent neural network classifier
    SVM.ipynb -> training, optimizing and showing performance of SVM classifier
    logistic_bayesian.ipynb -> training, optimizing and showing performance of logistic bayesian classifier    
  new_data: 
    X_coronavirus.csv -> input matrix of 1000 tweets of #coronavirus
    X_metoo.csv -> input matrix of 1000 tweets of #MeToo
    X_sparse.csv -> input matrix of training tweets in sparse format
    X_trump.csv -> input matrix of 1000 tweets of #Trump
    Y.csv -> input labels of training tweets
    combinedModel.sav -> stored trained combined model
    features.csv -> vocabulary features
  preprocess:
    BagOfWords_sparse.ipynb -> preprocessing training dataset to transfer them into matrix and store the larger matrix in sparse format
    Word2Vector.ipynb -> using Word2Vec library to represent words as a dictionry mapping words and their vectors
    preprocess_application_data.ipynb -> transfering tweets of three topics to matrix of 0 and 1 representing appearance of every feature vocabulary
    word2vec.model -> stored word2vec model
    
