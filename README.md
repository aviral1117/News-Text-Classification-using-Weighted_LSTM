# News_text Classification using Recurrent Neural Networks

Implementation of the paper: [Link](https://arxiv.org/abs/1909.13077)

Please download the pickle files(as used by the code) of the processed data using this link: [Data and Word2Vec Model](https://drive.google.com/drive/folders/1esbt0Z3nCl-Tu6Cp9JMIY-6-eH85v4PR?usp=sharing). 
The above link contains 5 files as follows:
- train_data.p : Used for training the model
- desired_train_data.p : Desired output values for the training data
- test_data.p : Used for testing the model
- desired_test_data.p : The actual expected results for the test data
- wordvectors1.kv : The word2vec model used to develop the word embeddings for the news text

The implementation uses the architecture as given in the above paper but a few modifications has been made to the hyperparameters and implementation specifications to improve on the same.

Original Dataset: [Link](http://qwone.com/~jason/20Newsgroups/)

Predictions.xlsx shows the result for the first 100 predictions.
