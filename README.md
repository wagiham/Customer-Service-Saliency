# Customer-Service-Saliency
This project trains and tests a ML model using data provided in He et al. (2020) which contains a multitude of customer service conversations through Twitter. 

There are 5 different human annotators identified each sentence in this data as salient or non-salient. Sometimes these annotations may disagree and not all five annotators voted on all sentences. Within this project, 1087 conversations were split into a train, test and validation dataset: tweetsum_train.csv, tweetsum_val.csv, tweetsum_test.csv. 
By dividing the data in this way, you can train the models with the training set, tune its hyperparameters using the validation set and finally test with the test set.

From this project, it's recommended that using distil BERT as the relatively high score of 0.75 roc_auc from the base model itself indicates that by hyper tuning the model we can achieve higher scores.

