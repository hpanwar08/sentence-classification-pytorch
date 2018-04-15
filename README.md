# Sentiment Analysis with Variable Length sequences in pytorch

This repo contains the code for the this blog.

## Prerequisites
* Basic knowledge of [Pytorch 0.3.1](http://pytorch.org/)
* Understanding of GRU/LSTM [4]

## What is covered in the [notebook](/Sentiment analysis pytorch.ipynb)

1. Load Data
2. Simple Data Analysis
3. Build Vocabulary and tokenize
4. Unpadded dataset and dataloader
5. Padded dataset and dataloader
6. Simple GRU model
6. GRU model with concat pooling
7. Max Pooling and Average Pooling
8. Train

## Data Overview

![GRU model with concat pooling](data/imgs/dfhead.png "GRU model with concat pooling")

## Output from GRU and hidden state
![GRU model with concat pooling](data/imgs/last_out.jpg "GRU output")

## Concat Pooling model architecture [5]
![GRU model with concat pooling](data/imgs/Slide2.JPG "GRU model with concat pooling")

## References
[1] http://thinknook.com/twitter-sentiment-analysis-training-corpus-dataset-2012-09-22/  
[2] http://thinknook.com/wp-content/uploads/2012/09/Sentiment-Analysis-Dataset.zip  
[3] https://stackoverflow.com/questions/46387661/how-to-correctly-implement-a-batch-input-lstm-network-in-pytorch  
[4] https://colah.github.io/posts/2015-08-Understanding-LSTMs/  
[5] https://arxiv.org/abs/1801.06146
