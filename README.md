# CNN-Based-Offensive_language_classification

## Steps to use CNN for text classification
   1.    Convert the words into dense vector form.
   2.    Each entry of the vector contains the real value which represents the similarities of words.
   3.    Apply 1D convolution over the Dense vector of the words.
   4.    We can use the n-gram concept in this approach by selecting one or more than one word vector at a time.
   5.    Use filter of size 3,4 or 5.
   6.    The result after convolution get the real value represents the similarity between the input words.
   7.    We use 100’s number of filter.
   8.    Each filter gives the result.
   9.    So we can use MLP over that.

## Methods and Parameters used in my project.
   1.    Removed the non-ascii words and punctuations.
   2.    Removed stop words.
   3.    Apply tokenization.
   4.    Used glove for word embedding.
   5.    Total number of filter used = 128
   6.    Embedding dimension = 100
   7.    Maximum sequence length = 1000
   8.    Kernel size = 5
   9.    Activation function = relu
   10.    Pooling = max pooling
   11.    Convolution layer = 3
   12.    Loss = binary cross entropy
   13.    Optimizer = adam

## Accuracy of the model
   F1 score = 76.78%