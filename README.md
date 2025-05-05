# text-classification-with-transformer-encoder

## Description
The aim of this notebook is to do text classification for the AG_news dataset (a similar procedure can be use to perform sentiment analysis). We build and train two different models: first we use only a bag of embedding to perform the classification, the second model we use is a Transformer encoder architecture. 

We train the model in a reduced dataset, due to the fact that the models are trained on cpu. 

As expected, the transformer-encoder architecture yielded a higher accuracy on the test set. Larger datasets can be considered if gpu's are used, as well as a deeper transformer-encoder architectures, which is expected to give better results. 
