# Customer Complaints Auto-Categorization: Performance Comparison of Recurrent Neural Network and Convolutional Neural Network

This code is based on my thesis project "Customer Complaints Auto-Categorization: Performance Comparison of Recurrent Neural Network and Convolutional Neural Network"

In this work, RNN and CNN’s performance in automatically classifying the CFPB Consumer
Complaints dataset was investigated and compared. The first research question is whether CNN
performs better than RNN in automatically classifying customer complaints. Furthermore, the
second question is whether the use of word2vec pre-trained word embeddings will improve both
classifiers’ performances.
To answer the questions, experiments to discover the Accuracy, Precision, Recall, F1 Score,
and training time of RNN and CNN based classifiers was attempted. The comparison approach
was to create classifiers with similar hyperparameter and number of parameters. Four types
of classifiers were compared in the experiments. RNN and CNN with word embeddings that
initialized from scratch and had the vector space of representations updated during training and
RNN and CNN with pre-trained static word-embeddings.
Based on the results of the accuracy scores of the experiments, RNN still performs better.
Moreover, based on the Training Time results, CNN with word2vec pre-trained word embeddings
performed the fastest. The results also revealed that word2vec pre-trained word embeddings
did not improve both architectures’ accuracy scores but significantly lower the architectures’
training time.
