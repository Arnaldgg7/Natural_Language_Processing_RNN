# Natural_Language_Processing_RNN
Using different Python Natural Language Processing techniques as well as MLP and Recurrent Neural Networks to perform tweets' Sentiment Analysis predictions.

This Google Colab consists in a Natural Language Processing pipeline in Python to pre-process, prepare and vectorize a dataset of tweets about US airlines and their respective tags in order to train a Natural Language Processing architecture with a Word Embeddings Table approach.

First, we train and use to predict a Multi-Layer Perceptron Neural Network with an arbitrary summarization operation, such as the Mean of the word vectors from the Word Embeddings Table. Then, in order to explain the expected outcomes when we tweak different parameters of the Neural Network architecture, we carry out such changes and we provide a rationale about the corresponding results. There are also some charts added aimed at explaining the training process of the Neural Network when fitting the data, and how such a process behaves when we modify the architecture.

Finally, a Recurrent Neural Network is applied, from which we make use of the Context Vector to determine the overall feeling of each tweet without any arbitrary summarization operation (such as the Mean we used in MLP), and see which results we get, and how they might be further improved.
